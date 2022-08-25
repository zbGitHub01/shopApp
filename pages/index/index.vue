<template>
	<view>
		<!-- #ifdef MP-WEIXIN -->
			<view class="small-app">
				<view class="iconfont icon-fangdajing"></view>
				<view>奥特莱斯大促销</view>
				<view class="iconfont icon-xiaoxi_o"></view>
			</view>
		<!-- #endif -->
		<!-- <view class="f-color">
			炎龙虾
		</view>
		<view class="iconfont icon-shangjiantou">
		</view> -->
	</view>
</template>

<script>
	
</script>

<style>
	.small-app{
		display: flex;
		/* line-height: 300rpx; */
		height: var(--status-bar-height);
		width: 100%;
		margin-top: 20%;
		justify-content: space-between;
	}
	.icon-fangdajing{
		margin-left: 2%;
		font-size: 50rpx;
	}
	.icon-xiaoxi_o{
		margin-right: 2%;
		font-size: 50rpx;
	}
</style>
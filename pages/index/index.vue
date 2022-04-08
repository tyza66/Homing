<template>
	<view>
		<view class="top"></view>
		<view class="title">
			<view class="left">
				<view class="p1"><image src="../../static/icons/wei.png"></image><p>锦州</p></view>
				<view class="p2"><p>您好，188****7909</p></view>
			</view>
			<view class="right">
				<view>
					<image src="../../static/icons/she.png"></image>
					<p>设置</p>
				</view>
				<view>
					<image src="../../static/icons/fa.png"></image>
					<p>发现</p>
				</view>
			</view>
		</view>
		<view class="items">
			<view class="item">
				<image src="../../static/icons/fi1.png"></image>
				<p>会员</p>
			</view>
			<view class="item">
				<image src="../../static/icons/fi2.png"></image>
				<p>活动</p>
			</view>
			<view class="item">
				<image src="../../static/icons/fi3.png"></image>
				<p>附近</p>
			</view>
			<view class="item">
				<image src="../../static/icons/fi4.png"></image>
				<p>冠军</p>
			</view>
			<view class="item">
				<image src="../../static/icons/fi5.png"></image>
				<p>积分</p>
			</view>
			<view class="item">
				<image src="../../static/icons/fi6.png"></image>
				<p>评论</p>
			</view>
			<view class="item">
				<image src="../../static/icons/fi7.png"></image>
				<p>运动</p>
			</view>
			<view class="item">
				<image src="../../static/icons/fi8.png"></image>
				<p>生活休闲</p>
			</view>
		</view>
		<view class="buttom">
			<view class="left1">
				<image src="../../static/icons/chong1.png"></image>
				<p>普通模式</p>
			</view>
			<view class="right1">
				<image src="../../static/icons/chong2.png"></image>
				<p>关怀模式</p>
			</view>
		</view>
		<view class="xia">
			<view class="xiaoxia">
				<p class="a1">渤海大学滨海小区回海城市...</p>
				<p class="a2">查看详情</p>
			</view>
			<view class="xiaoxia">
				<p class="a1">渤海大学滨海小区回七台河市...</p>
				<p class="a2">查看详情</p>
			</view>
			<view class="xiaoxia">
				<p class="a1">渤海大学滨海小区回天津市...</p>
				<p class="a2">查看详情</p>
			</view>
			<view class="xiaoxia">
				<p class="a1">渤海大学滨海小区回密山市...</p>
				<p class="a2">查看详情</p>
			</view>
			<view class="xiaoxia">
				<p class="a1">渤海大学滨海小区回鹤岗市...</p>
				<p class="a2">查看详情</p>
			</view>
			<view class="xiaoxia">
				<p class="a1">渤海大学滨海小区回宁安市...</p>
				<p class="a2">查看详情</p>
			</view><view class="xiaoxia">
				<p class="a1">渤海大学滨海小区回佳木斯市...</p>
				<p class="a2">查看详情</p>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	.top {
		height: var(--status-bar-height);
		width: 100%;
		background-color: #FFFFFF;
	}
	.title{
		height: 180rpx;
		width: 100%;
	}
	.left{
		float: left;
		width: 400rpx;
		height: 160rpx;
		margin-top: 10rpx;
		display: flex;
		flex-direction: column;
		justify-content: left;
		align-items: left;
	}
	.p1{
		margin-left: 20rpx;
		height: 80rpx;
		display: flex;
		flex-direction: row;
		justify-content: left;
		align-items: center;
	}
	.p1 image{
		width: 50rpx;
		height: 50rpx;
	}
	.p1 p{
		display: inline;
		font-size: 36rpx;
		font-weight: 550;
	}
	.p2{
		margin-left: 20rpx;
		height: 50rpx;
		display: flex;
		flex-direction: row;
		justify-content: left;
		align-items: center;
	}
	.p2{
		color: #999999;
		font-size: 35rpx;
	}
	.right{
		float: right;
		width: 220rpx;
		height: 160rpx;
		margin-top: 10rpx;
		display: flex;
		flex-direction: row;
		justify-content: left;
		align-items: center;
	}
	.right view{
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		margin: 0 auto;
	}
	.right view image{
		width: 80rpx;
		height: 80rpx;
	}
	.right view p{
		font-weight: 500;
	}
	.items{
		flex-wrap: wrap;
		width: 100%;
		height: 360rpx;
		display: flex;
		flex-direction: row;
		justify-content: center;
		align-items: center;
	}
	.item{
		width: 180rpx;
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
	}
	.item image{
		width: 80rpx;
		height: 80rpx;
	}
	.item p{
		font-size: 30rpx;
		color: #555555;
	}
	.buttom{
		width: 100%;
		height: 300rpx;
	}
	.buttom .left1{
		float: left;
		width: 330rpx;
		height: 300rpx;
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		background: #F8AE55;
		margin-left: 35rpx;
		border-radius: 15rpx;
	}
	.buttom image{
		width: 180rpx;
		height: 180rpx;
	}
	.buttom .right1{
		float: right;
		width: 330rpx;
		height: 300rpx;
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		background: #F8AE55;
		margin-right: 35rpx;
		border-radius: 15rpx;
	}
	.buttom p{
		color: #FFFFFF;
		font-size: 40rpx;
	}
	.xia{
		width: 680rpx;
		margin: 0 auto;
	}
	.xiaoxia{
		width: 100%;
		height: 100rpx;
		background: #F9CC97;
		margin-top: 15rpx;
		border-radius: 10rpx;
		position: relative;
	}
	.xiaoxia .a1{
		position: absolute;
		left: 24rpx;
		top: 28rpx;
	}
	.xiaoxia .a2{
		position: absolute;
		left: 520rpx;
		top: 28rpx;
		color: #808080;
	}
</style>

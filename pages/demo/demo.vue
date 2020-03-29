<template>
	<view>
		<!-- <view class="view-box animated" id="view2">第一个view</view>
		<text>text组件</text> -->
		
		<!-- <view class="box">
			<text>text组件</text>
			<view>1</view>
			<view>2</view>
			<view>3</view>
		</view> -->
		
		<!-- <view class="box">
			<view class="box-item">1</view>
			<view class="box-item">2</view>
			<view class="box-item">3</view>
			<view class="box-item">4</view>
			<view class="box-item">5</view>
			<view class="box-item">6</view>
			<view class="box-item">7</view>
			<view class="box-item">8</view>
		</view> -->
		
		<view class="box">
			<view class="box-item">测试一</view>
			<view class="box-item">测试二</view>
			<view class="box-item">测试三</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		methods: {
			
		}
	}
</script>

<style>
/* .view-box {
	width: 200upx;
	height: 200upx;
	background: #007AFF;
	color: #FFFFFF;
	margin: 100upx;
}
.view-box-hover {
	background: #09BB07;
}
.box {
	width: 300upx;
	height: 300upx;
	background: #007AFF;
	color: #FFFFFF;
	margin: 100upx;
	padding: 50upx;
}
.box view {
	font-size: 40upx;
}
.box view:nth-of-type(1) {
	background: #576B95;
}
.box view:nth-of-type(2) {
	background: red;
}
.box view:nth-of-type(3) {
	background: #8A6DE9;
} */
/* .box {
	height: 500upx;
	width: 100%;
	border: 1upx solid #CCCCCC;
	display: flex;
	flex-wrap: wrap;
	justify-content: center;
	align-items: center;
}
.box-item {
	background: #007AFF;
	color: #FFFFFF;
	width: 200upx;
	height: 200upx;
	line-height: 200upx;
	font-size: 30upx;
	text-align: center;
	font-weight: bold;
}
.box-item:nth-of-type(old) {
	background: #007AFF;
}
.box-item:nth-of-type(even) {
	background: #09BB07;
} */
.box {
	border: 1upx solid #ccc;
	height: 500upx;
	width: 100%;
	display: flex;
}
.box > view {
	background: #007AFF;
	color: #FFFFFF;
	font-weight: bold;
	font-size: 40upx;
	flex: 1;
	height: 500upx;
	display: flex;
	justify-content: center;
	align-items: center;
	border: 1upx solid #FFFFFF;
}
</style>

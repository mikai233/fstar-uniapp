<template>
	<view>
		<cover-image src="http://resource.mdreamfever.com/logo.png" class="logo"></cover-image>
		<view class="title">繁星课程表</view>
		<view class="text">繁星课程表是由个人开发的一款江苏科技大学专用的课程表软件，此版本为小程序版本，另有Android版本（可在酷安下载）</view>
		<view class="text">数据来源为江苏科技大学教务系统，本软件只对教务系统做简单对接，不保证教务系统以及本软件服务的稳定性，如发生问题，还请谅解</view>
		<view class="text">作者QQ 1048429035</view>
		<text class="copy-right">Copyright © 2021 mdreamfever, all rights reserved.</text>
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
	.logo {
		width: 30%;
		border-radius: 100%;
		margin: 100rpx auto;
	}

	.title {
		text-align: center;
		font-weight: bold;
		margin: 20rpx;
	}

	.text {
		margin: 20rpx;
		font-size: .8em;
		text-align: center;
	}
</style>

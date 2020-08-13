<template>
	<view>
		<text>1</text>
		<navigator url="/pages/about/about">2222222</navigator>
		<view>211111111111</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		methods: {
			
		},
		onShow() {
			console.log('onShow')
		},
		onPullDownRefresh() {
			console.log('onPullDownRefresh')
		},
		beforeCreate() {
			console.log('beforeCreate')
		},
		mounted() {
			console.log('mounted',getApp(),getApp().globalData,getCurrentPages(),this.$scope)
			// #ifdef APP-PLUS
			    console.log(this.$scope.$getAppWebview())
			// #endif
		}
	}
</script>

<style lang="scss">

</style>

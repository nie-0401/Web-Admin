<template>
	<div class="dashboard-container">
		<img class="dashboard-img" src="https://raw.githubusercontent.com/nie-0401/image_storage/master/20211223/pexels-photo-3075993.l3dc8f3htf4.jpeg" alt="">
		<div class="dashboard-text">Welcome To My Admin</div>
	</div>
</template>

<script>
	export default {
		name: 'My-Admin',
	}
</script>

<style lang="scss" scoped>
.dashboard {
	&-container {
		width: 100%;
		height: 100vh;
		position: relative;
	}
	&-img {
		position: absolute;
		top: 0;
		left: 0;
	}
	&-text {
		font-size: 30px;
		color: #fff;
		line-height: 46px;
		position: absolute;
		top: 50%;
		left: 50%;
		transform: translate(-50%, -50%);
		z-index: 999;
	}
}
</style>

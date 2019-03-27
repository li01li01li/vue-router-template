<template>
	<div class="container">
		<div class="side-bar">
			
			<div class="wenzi">
			<h2>库成分</h2>
			<h2>管理</h2>
			</div>
			<router-link to="/all">全部</router-link>
			
		</div>
		<div class="content"><router-view /></div>
	</div>
</template>

<script>
export default {
	name: 'Lib',
	data() {
		return {
			
		};
	}
};
</script>

<style scoped>
	.container{
		display: flex;
		width: 90%;
		margin: 0 auto;
	}
	a{
		margin-bottom: 30px;
	}
	.side-bar{
		flex: 1 1 20%;
		display: flex;
		flex-direction: column;
		background-color: #fff;
		margin-top: 20px;
	}
	.wenzi{
		
		justify-content: space-between;
	}
	.content{
		flex: 1 1 80%;
		background-color: #fff;
		margin-left: 20px;
		padding-bottom: 20px;
	}
</style>

<template>
	<div id="app">
		<div id="nav">
			<div class="nav-content">
				<div class="login">
					<span>Welcome to Your Vue.js App</span>
					<router-link to="/">sign</router-link>
				</div>
				<div class="nav-router">
					<router-link to="/">Home</router-link> |
					<router-link to="/about">About</router-link> |
					<router-link to="/News">News</router-link>
				</div>
			</div>

		</div>
		<router-view/>
	</div>
</template>

<style>
	@import url('assets/css/common/common.css');
</style>

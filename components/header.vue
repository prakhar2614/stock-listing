<template lang="pug">
.nav 
	.start 
		.p HOME       
		.p SCREENS 
		.p TOOLS
		i.mi arrow_drop_down
	.end 
		.p Login
		.p Create Account
</template>

<style lang="sass">
.nav
	display: flex
	justify-content: space-around
	font-size: 3rem
	background: red
	.start
		cursor: pointer
		display: flex
		justify-content: space-evenly		
	.end
		cursor: pointer
		display: flex
		justify-content: space-evenly
</style>
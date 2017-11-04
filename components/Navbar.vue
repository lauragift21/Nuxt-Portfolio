<template>
	<div class="container">
		<nav class="navbar" role="navigation" arial-label="main navigation">
			<div class="navbar-brand">
				<a href="/" class="navbar-item">Portfolio</a>
				<button class="button navbar-burger">
					<span></span>
					<span></span>
					<span></span>
				</button>
			</div>
			<div class="navbar-menu">
				<!-- NavBar Link using vue router -->
				<div class="navbar-end">
					<nuxt-link class="navbar-item" to="/">Home</nuxt-link>
					<nuxt-link class="navbar-item" to="/about">About</nuxt-link>
					<nuxt-link class="navbar-item" to="/projects">Projects</nuxt-link>
					<nuxt-link class="navbar-item" to="/contact">Contact</nuxt-link>
				</div>
			</div>
		</nav>
	</div>
</template>
<template>
  <router-view/>
</template>

<script>

</script>

<style>
.linkText {
  font-family: Poppins, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: gray;
}

a {
	margin-left: 10px;
	font-style: normal;
	font-weight: 600;
	font-size: 24px;
	/* line-height: 70px; */
	color: #747474;
}

a:link {
	text-decoration: none;	
}

a:visited {
	text-decoration: none;
}

a:hover {
  color: black;
  text-decoration: underline;
}

a:active {
	color: black;
  text-decoration: underline;
}

h1:hover {
	color: black;
}

/* nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
} */
</style>

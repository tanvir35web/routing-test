<template>
    <div class="nav-bar">
        <NuxtLink class="nav-link" active-class="active" to="/">Home</NuxtLink>
        <NuxtLink class="nav-link" active-class="active" to="/profile">Profile</NuxtLink>
        <NuxtLink class="nav-link" active-class="active" to="/contact">Contact</NuxtLink>
        <NuxtLink class="nav-link" active-class="active" to="/about">About</NuxtLink>
    </div>
</template>

<style>
.nav-bar {
   background: #d9ebd0;
   padding: 15px;
   border-radius: 10px;
}
.active {
    background: #7da75e;
}
.nav-link {
    color: black;
    text-decoration: none;
    font-size: 20px;
    padding: 10px;
    margin-right: 20px;
    border-radius: 6px;
}
</style>

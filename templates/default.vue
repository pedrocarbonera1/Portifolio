<template>
    <div>
        <header>
            <nav>
                <NuxtLink to="/">Home</NuxtLink>
                <NuxtLink to="/about.vue">Sobre</NuxtLink>
            </nav>
        </header>
        <main>
            <slot />
        </main>
        <footer>
            <p>© 2025 - Meu Site</p>
        </footer>
    </div>
</template>
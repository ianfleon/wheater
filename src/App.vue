<script setup>
    import HelloWorld from './components/HelloWorld.vue'
    import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
    <section class="section">
        <div class="container">
            <div class="columns">
                <div class="column is-4">
                    <div class="mb-4">
                        <h4>Today</h4>
                        <p>Wed, 16 Oct 2024</p>
                    </div>
                    <div class="mb-4">
                        <h2 class="title is-1">34°</h2>
                    </div>
                    <div class="is-flex flex-direction-row">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 0c-4.198 0-8 3.403-8 7.602 0 6.243 6.377 6.903 8 16.398 1.623-9.495 8-10.155 8-16.398 0-4.199-3.801-7.602-8-7.602zm0 11c-1.657 0-3-1.343-3-3s1.342-3 3-3 3 1.343 3 3-1.343 3-3 3z"/></svg>
                        <h4>Kota Mataram, Nusa Tenggara Barat</h4>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
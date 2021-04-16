<template>
    <div class="container">
        <Step></Step>
        <Info></Info>
        <main>
            <router-view/>
        </main>
    </div>
</template>

<script>
import Info from '@/components/Info.vue';
import Step from '@/components/Step.vue';
export default {
    components: {
        Info,
        Step,
    },
}
</script>

<style src="@/assets/sass/style.scss" lang="scss"></style>

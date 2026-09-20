<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="irlyeabhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:tornado-thin" /></template>
<style>
.irlyeabhs {
  fill: currentColor;
  d: path("M228 40a4 4 0 0 1-4 4H56a4 4 0 0 1 0-8h168a4 4 0 0 1 4 4m-48 32a4 4 0 0 0-4-4H32a4 4 0 0 0 0 8h144a4 4 0 0 0 4-4m-16 32a4 4 0 0 0-4-4H56a4 4 0 0 0 0 8h104a4 4 0 0 0 4-4m16 32a4 4 0 0 0-4-4H88a4 4 0 0 0 0 8h88a4 4 0 0 0 4-4m4 28h-64a4 4 0 0 0 0 8h64a4 4 0 0 0 0-8m-24 32h-32a4 4 0 0 0 0 8h32a4 4 0 0 0 0-8m-32 32h-16a4 4 0 0 0 0 8h16a4 4 0 0 0 0-8");
}

</style>

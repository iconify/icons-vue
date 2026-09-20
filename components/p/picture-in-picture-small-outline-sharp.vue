<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epygqxank"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:picture-in-picture-small-outline-sharp" /></template>
<style>
.epygqxank {
  fill: currentColor;
  d: path("M3 19v-1h17V5h1v14zm6.923-3.384V9.923h7.693v5.693z");
}

</style>

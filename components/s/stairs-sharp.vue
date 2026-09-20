<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9mpf1blt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stairs-sharp" /></template>
<style>
.g9mpf1blt {
  fill: currentColor;
  d: path("M6.5 17.5h3.425v-3.325H12.5V10.85h2.575V7.5H17.5v-1h-3.425v3.325H11.5v3.325H8.925v3.35H6.5zM4 20V4h16v16z");
}

</style>

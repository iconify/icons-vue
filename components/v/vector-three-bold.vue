<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="z52544mky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:vector-three-bold" /></template>
<style>
.z52544mky {
  fill: currentColor;
  d: path("m240.49 144.49l-32 32a12 12 0 0 1-17-17L203 148h-78l-48 48h19a12 12 0 0 1 0 24H48a12 12 0 0 1-12-12v-48a12 12 0 0 1 24 0v19l48-48V53L96.49 64.49a12 12 0 1 1-17-17l32-32a12 12 0 0 1 17 0l32 32a12 12 0 0 1-17 17L132 53v71h71l-11.52-11.51a12 12 0 0 1 17-17l32 32a12 12 0 0 1 .01 17");
}

</style>

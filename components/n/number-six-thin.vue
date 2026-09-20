<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="hl0tjhlox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:number-six-thin" /></template>
<style>
.hl0tjhlox {
  fill: currentColor;
  d: path("M128 108a51.66 51.66 0 0 0-24.74 6.27L139.49 50a4 4 0 0 0-7-3.92L83 134.05A52 52 0 1 0 128 108m0 96a44 44 0 1 1 44-44a44.05 44.05 0 0 1-44 44");
}

</style>

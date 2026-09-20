<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="m9rwm-blo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:number-square-two-thin" /></template>
<style>
.m9rwm-blo {
  fill: currentColor;
  d: path("M208 36H48a12 12 0 0 0-12 12v160a12 12 0 0 0 12 12h160a12 12 0 0 0 12-12V48a12 12 0 0 0-12-12m4 172a4 4 0 0 1-4 4H48a4 4 0 0 1-4-4V48a4 4 0 0 1 4-4h160a4 4 0 0 1 4 4Zm-56-32a4 4 0 0 1-4 4h-48a4 4 0 0 1-3.2-6.4L144 116a20 20 0 0 0-4-28a20 20 0 0 0-28 4a20.2 20.2 0 0 0-2.89 5.37a4 4 0 0 1-7.55-2.66a28.3 28.3 0 0 1 4-7.52a28 28 0 1 1 44.72 33.7L112 172h40a4 4 0 0 1 4 4");
}

</style>

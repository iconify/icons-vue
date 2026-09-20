<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="rxhmk53ki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:sort-descending-fill" /></template>
<style>
.rxhmk53ki {
  fill: currentColor;
  d: path("M208 32H48a16 16 0 0 0-16 16v160a16 16 0 0 0 16 16h160a16 16 0 0 0 16-16V48a16 16 0 0 0-16-16M72 72h40a8 8 0 0 1 0 16H72a8 8 0 0 1 0-16m0 48h48a8 8 0 0 1 0 16H72a8 8 0 0 1 0-16m96 64H72a8 8 0 0 1 0-16h96a8 8 0 0 1 0 16m29.66-82.34a8 8 0 0 1-11.32 0L176 91.31V136a8 8 0 0 1-16 0V91.31l-10.34 10.35a8 8 0 0 1-11.32-11.32l24-24a8 8 0 0 1 11.32 0l24 24a8 8 0 0 1 0 11.32");
}

</style>

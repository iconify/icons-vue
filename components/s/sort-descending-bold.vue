<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="truhol4jc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:sort-descending-bold" /></template>
<style>
.truhol4jc {
  fill: currentColor;
  d: path("M36 128a12 12 0 0 1 12-12h68a12 12 0 0 1 0 24H48a12 12 0 0 1-12-12m12-52h52a12 12 0 0 0 0-24H48a12 12 0 0 0 0 24m132 104H48a12 12 0 0 0 0 24h132a12 12 0 0 0 0-24m52.49-100.49l-40-40a12 12 0 0 0-17 0l-40 40a12 12 0 0 0 17 17L172 77v67a12 12 0 0 0 24 0V77l19.51 19.52a12 12 0 0 0 17-17Z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="xpwy6fjug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:oven-fill" /></template>
<style>
.xpwy6fjug {
  fill: currentColor;
  d: path("M208 32H48a16 16 0 0 0-16 16v160a16 16 0 0 0 16 16h160a16 16 0 0 0 16-16V48a16 16 0 0 0-16-16m-36 24a12 12 0 1 1-12 12a12 12 0 0 1 12-12m-44 0a12 12 0 1 1-12 12a12 12 0 0 1 12-12m-44 0a12 12 0 1 1-12 12a12 12 0 0 1 12-12m108 136H64v-88h128Z");
}

</style>

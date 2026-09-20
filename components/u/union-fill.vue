<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="nowg_l6_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:union-fill" /></template>
<style>
.nowg_l6_l {
  fill: currentColor;
  d: path("M208 32H48a16 16 0 0 0-16 16v160a16 16 0 0 0 16 16h160a16 16 0 0 0 16-16V48a16 16 0 0 0-16-16m-24 104a56 56 0 0 1-112 0V80a8 8 0 0 1 16 0v56a40 40 0 0 0 80 0V80a8 8 0 0 1 16 0Z");
}

</style>

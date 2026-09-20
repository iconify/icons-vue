<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vd3ibqb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:radical-fill" /></template>
<style>
.vd3ibqb5g {
  fill: currentColor;
  d: path("M208 32H48a16 16 0 0 0-16 16v160a16 16 0 0 0 16 16h160a16 16 0 0 0 16-16V48a16 16 0 0 0-16-16m0 80a8 8 0 0 1-16 0v-8h-66.58l-30 75a8 8 0 0 1-14.86 0l-32-80a8 8 0 1 1 14.87-6L88 154.46L112.57 93a8 8 0 0 1 7.43-5h80a8 8 0 0 1 8 8Z");
}

</style>

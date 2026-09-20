<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="f4z89fbbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:traffic-signal-fill" /></template>
<style>
.f4z89fbbg {
  fill: currentColor;
  d: path("M216 144h-16V80h16a8 8 0 0 0 0-16h-16V40a16 16 0 0 0-16-16H72a16 16 0 0 0-16 16v24H40a8 8 0 0 0 0 16h16v64H40a8 8 0 0 0 0 16h16v56a16 16 0 0 0 16 16h112a16 16 0 0 0 16-16v-56h16a8 8 0 0 0 0-16m-88-28a28 28 0 1 1 28-28a28 28 0 0 1-28 28m0 24a28 28 0 1 1-28 28a28 28 0 0 1 28-28");
}

</style>

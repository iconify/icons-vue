<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ml-la-68f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:superset-proper-of-fill" /></template>
<style>
.ml-la-68f {
  fill: currentColor;
  d: path("M208 32H48a16 16 0 0 0-16 16v160a16 16 0 0 0 16 16h160a16 16 0 0 0 16-16V48a16 16 0 0 0-16-16m-80 160H80a8 8 0 0 1 0-16h48a48 48 0 0 0 0-96H80a8 8 0 0 1 0-16h48a64 64 0 0 1 0 128");
}

</style>

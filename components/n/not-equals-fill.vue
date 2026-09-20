<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="bn1kn7bnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:not-equals-fill" /></template>
<style>
.bn1kn7bnu {
  fill: currentColor;
  d: path("M208 32H48a16 16 0 0 0-16 16v160a16 16 0 0 0 16 16h160a16 16 0 0 0 16-16V48a16 16 0 0 0-16-16m-24 112a8 8 0 0 1 0 16h-73.37L78 197.27a8 8 0 0 1-12-10.54L89.37 160H72a8 8 0 0 1 0-16h31.37l28-32H72a8 8 0 0 1 0-16h73.37L178 58.73a8 8 0 1 1 12 10.54L166.63 96H184a8 8 0 0 1 0 16h-31.37l-28 32Z");
}

</style>

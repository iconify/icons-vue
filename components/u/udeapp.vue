<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jx0kjebyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:udeapp" /></template>
<style>
.jx0kjebyv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.655 35.892a3.864 3.864 0 0 1 3.712 3.886a3.71 3.71 0 0 1-3.712 3.712M7.44 8.213a3.712 3.712 0 1 1 7.425 0v0l.01 18.79h0a9.04 9.04 0 0 0 9.186 8.883a9.04 9.04 0 0 0 9.185-8.884h0l-.11-18.79a3.712 3.712 0 1 1 7.425 0V26.94a16.56 16.56 0 0 1-33.12 0z");
}

</style>

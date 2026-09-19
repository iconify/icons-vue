<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eduokpz-y"/><path class="aj65c0n0d"/><path class="wowd3ebdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-unfold-more-double" /></template>
<style>
.aj65c0n0d {
  fill: currentColor;
  d: path("M9.53 10.29L12 7.83l2.46 2.46a.996.996 0 1 0 1.41-1.41L12.7 5.7a.996.996 0 0 0-1.41 0L8.12 8.88a.996.996 0 1 0 1.41 1.41m4.94 3.42L12 16.17l-2.46-2.46a.996.996 0 1 0-1.41 1.41l3.17 3.18c.39.39 1.02.39 1.41 0l3.17-3.18a.996.996 0 1 0-1.41-1.41");
}

.eduokpz-y {
  fill: currentColor;
  d: path("M9.53 5.29L12 2.83l2.46 2.46a.996.996 0 1 0 1.41-1.41L12.7.7a.996.996 0 0 0-1.41 0L8.12 3.88a.996.996 0 1 0 1.41 1.41");
}

.wowd3ebdb {
  fill: currentColor;
  d: path("M14.47 18.72L12 21.17l-2.46-2.46a.996.996 0 1 0-1.41 1.41l3.17 3.18c.39.39 1.02.39 1.41 0l3.17-3.17a.996.996 0 1 0-1.41-1.41");
}

</style>

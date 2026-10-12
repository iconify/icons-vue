<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zl-llzbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:taurus-sharp" /></template>
<style>
.zl-llzbzh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 9.75a5.25 5.25 0 1 1 0 10.5a5.25 5.25 0 1 1 0-10.5m-8.25-6c1 3 3.75 5.75 8.25 5.75s7.25-2.75 8.25-5.75");
}

</style>

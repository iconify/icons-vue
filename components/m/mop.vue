<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fpgq5z5qp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mop" /></template>
<style>
.fpgq5z5qp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5V11m-4.5 0h9v3h-9Zm1 3L6 21.5m4.75-7.5L10 21.5m3.25-7.5l.75 7.5m1.5-7.5l2.5 7.5");
}

</style>

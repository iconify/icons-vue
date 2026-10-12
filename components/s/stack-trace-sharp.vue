<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbzqjtx2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:stack-trace-sharp" /></template>
<style>
.gbzqjtx2n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.26 4.11l2.23 3.78l.51.86H2.5l.51-.86l2.23-3.78l.51-.86zM12 6.25h9.25m-18.5 6h12M6.25 16h12.5m-9 3.75h11.5");
}

</style>

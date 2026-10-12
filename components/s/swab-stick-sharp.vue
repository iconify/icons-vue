<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xk2sowbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:swab-stick-sharp" /></template>
<style>
.xk2sowbcr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 20.25L14.5 9.5m4.69-4.55l-.14-.14l-1.34-1.34l-1.34 1.34l-1.56 1.56l-1.34 1.34l1.34 1.34l.14.14l1.34 1.34l1.34-1.34l1.56-1.56l1.34-1.34z");
}

</style>

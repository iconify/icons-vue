<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ourri2xtl"/><path class="fbagkkwbm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:white-cane" /></template>
<style>
.fbagkkwbm {
  fill: currentColor;
  d: path("m8.535 14.495l1.97 1.54l-1.54 1.97l-1.97-1.54Zm-2 2.25l1.97 1.54l-1.54 1.97l-1.97-1.54Z");
}

.ourri2xtl {
  d: path("m18 4.5l-13.5 17M18 4.5c.75-1.5 2.75-1.75 3.25-.25c.25.75 0 1.5-.75 2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

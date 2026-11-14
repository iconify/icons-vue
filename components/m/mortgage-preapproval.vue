<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zcgwlf0tm"/><path class="w25brbc8i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mortgage-preapproval" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w25brbc8i {
  d: path("M16 7V4h2v4.75m-2.25 8.75l1.5-2.75c.5-.5 1.5-.25 1.5.5v1.5h1.5a1 1 0 0 1 1 1l-.5 2.5a1 1 0 0 1-1 .75h-4Zm-1.5 0V21");
}

.zcgwlf0tm {
  d: path("M11.46 20.5H4v-10l8-7l8 7v1.84");
}

</style>

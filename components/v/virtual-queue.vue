<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b9xzdnbjl"/><path class="ybdau2bxm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:virtual-queue" /></template>
<style>
.b9xzdnbjl {
  d: path("M11.4 21.5H4v-19h12.5v10.2M7 7h6.5m-6.25 4h.01m2.99 0h.01m2.99 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ybdau2bxm {
  d: path("M14.25 15.5h7.5v1.75a1.25 1.25 0 0 0 0 2.5v1.75h-7.5v-1.75a1.25 1.25 0 0 0 0-2.5Z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="st6i_zbqe"/><path class="id18rfb-n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pill-water" /></template>
<style>
.id18rfb-n {
  d: path("m8.027 4.568l6.578-2.394l1.368 3.758l-6.578 2.394Z");
}

.st6i_zbqe {
  d: path("M5.5 8L7 21.5h10L18.5 8M6.25 14.75h11.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

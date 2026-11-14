<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hinjj0bwd"/><path class="p5uc4-iyg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:vulnerable-dependency" /></template>
<style>
.hinjj0bwd {
  d: path("M13.993 15.183L9.5 17.75l-7-4V6l7-4l7 4v4.038");
}

.p5uc4-iyg {
  d: path("m2.5 6l7 3.75l7-3.75m-7 3.75v8m8.5-4.5l4 8.25h-8Zm0 3.25v1.75M18 20h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

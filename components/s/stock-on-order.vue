<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l3hfmabci"/><path class="e372up6fs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stock-on-order" /></template>
<style>
.e372up6fs {
  d: path("m3 7l9 4.5L21 7m-9 4.5v8.6m0 .8v.6M7.5 4.75l9 4.5m5 5.25l-6 6m0-4v4h4");
}

.l3hfmabci {
  d: path("m12.38 21.31l-.38.19L3 17V7l9-4.5L21 7v4.038");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

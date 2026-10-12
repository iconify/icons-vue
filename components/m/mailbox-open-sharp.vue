<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="yf_l_wbvj"/><path class="ubft6ubwj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mailbox-open-sharp" /></template>
<style>
.ubft6ubwj {
  d: path("M11.25 19v-6.5l.001-1.657L10.08 9.67M14.5 19v2.25M17 13V2.75h3.5V5.5H17");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yf_l_wbvj {
  d: path("M7 8h14.25v11H2.75V8z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ewpklhbkw"/><path class="obuv2kbnf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rfid" /></template>
<style>
.ewpklhbkw {
  d: path("m3.25 9l4.5-4.5l4.5 4.5v11h-9Z");
}

.obuv2kbnf {
  d: path("M6.25 10.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm9-1a4.5 4.5 0 0 1 0 7m3-9.5a7 7 0 0 1 0 11");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

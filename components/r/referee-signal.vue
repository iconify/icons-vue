<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v5mhhbofc"/><path class="wks5ymklo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:referee-signal" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v5mhhbofc {
  d: path("M7.75 6a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.wks5ymklo {
  d: path("M5.25 21.5v-5a4 4 0 0 1 4-4h9.5v-9m-3.5 12v6");
}

</style>

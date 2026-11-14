<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w22-eyepo"/><path class="cmgw9rb2a"/><path class="wti3g3byz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:store-clock" /></template>
<style>
.cmgw9rb2a {
  d: path("M4.5 9.5v11h6.9m8.1-9.5V9.5m-6 8a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w22-eyepo {
  d: path("m3 7l1.5-4.5h15L21 7a3 3 0 0 1-6 0a3 3 0 0 1-6 0a3 3 0 0 1-6 0");
}

.wti3g3byz {
  d: path("M17.5 15.5v2l1.5 1");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fbud7vw1l"/><path class="j2jbgvn3s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:web3-login" /></template>
<style>
.fbud7vw1l {
  d: path("M6 8.5V7a2 2 0 0 1 2-2h11.5a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2v-1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j2jbgvn3s {
  d: path("M21.5 9.5h-4a2.5 2.5 0 0 0 0 5h4M2.5 12h9m-3-2.5L11 12l-2.5 2.5");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="gnua_btep"/><path class="mv13v_btl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:political-party-sharp" /></template>
<style>
.gnua_btep {
  cx: 9.5px;
  cy: 9.25px;
  r: 2.25px;
}

.mv13v_btl {
  d: path("M5 21.25v-2.5a4.5 4.5 0 0 1 9 0v2.5Zm12 0V7m0-4h4.25L20 5l1.25 2H17Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

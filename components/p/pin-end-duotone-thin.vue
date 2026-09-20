<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p67gkiiyp"/><path class="n3ly_qrui"/><path class="qad3kqbgr"/><path class="gvs6g-b0k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pin-end-duotone-thin" /></template>
<style>
.gvs6g-b0k {
  d: path("M9.5 7.5h5v5h-5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n3ly_qrui {
  fill: currentColor;
  d: path("M9.5 7.5h5v5h-5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.p67gkiiyp {
  fill: currentColor;
  d: path("M4 10a8 8 0 0 1 16 0l-8 8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.qad3kqbgr {
  d: path("M4 10a8 8 0 0 1 16 0l-8 8Z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="mkor9d5zf"/><path class="zrnuaslnh"/><path class="qutk18-3b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:school-building-sharp" /></template>
<style>
.mkor9d5zf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.5V12H8.5V9l.57-.49l2.36-2.02L12 6l.57.49l2.36 2.02l.57.49v3h5.75v9.25H2.75zM12 6V2.75l3 1.1l-3 1.1");
}

.qutk18-3b {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 21.25V18h3v3.25m-8.25-5.5h1.5m10.5 0h1.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zrnuaslnh {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 10.5h.01");
}

</style>

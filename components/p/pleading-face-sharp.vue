<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="dbgvcxwad"/><path class="stvj_3i7l"/><circle class="re_w6mbga"/><circle class="g06yjb6bk"/><path class="da8y-2bxi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pleading-face-sharp" /></template>
<style>
.da8y-2bxi {
  d: path("m10.5 17l1.5-.9l1.5.9");
}

.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.g06yjb6bk {
  cx: 15px;
  cy: 11.25px;
  r: 2px;
}

.re_w6mbga {
  cx: 9px;
  cy: 11.25px;
  r: 2px;
}

.stvj_3i7l {
  d: path("M7.25 8.25L9.75 7m7 1.25L14.25 7");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

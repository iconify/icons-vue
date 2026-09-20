<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pi39ped8z"/><path class="vw4rulbpx"/><path class="zoa0-pbyv"/><path class="oj85lec1z"/><path class="p1h-ezbbv"/><path class="hgui8bcaa"/><path class="lhfoj2bfk"/><path class="olup7y72x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:type-error-duotone-thin" /></template>
<style>
.hgui8bcaa {
  d: path("m17 7 2.5 2.5L17 12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lhfoj2bfk {
  d: path("M12 6v4.5");
}

.oj85lec1z {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 6v4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.olup7y72x {
  d: path("M11 13.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.p1h-ezbbv {
  d: path("M7 7 4.5 9.5 7 12");
}

.pi39ped8z {
  fill: currentColor;
  d: path("M11 13.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.vw4rulbpx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 7 4.5 9.5 7 12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zoa0-pbyv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m17 7 2.5 2.5L17 12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

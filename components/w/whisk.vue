<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hc6zpmbpr"/><rect class="cbthhphrh"/><path class="j_itcabqc"/><path class="dt6buif6s"/><path class="jfl86sb5a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:whisk" /></template>
<style>
.cbthhphrh {
  width: 14px;
  height: 2.5px;
  x: 5px;
  y: 6px;
  rx: 1.25px;
}

.dt6buif6s {
  d: path("M8.25 8.5v4.25a3.75 6 0 0 0 7.5 0V8.5");
}

.hc6zpmbpr {
  d: path("M12 2.75V6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j_itcabqc {
  d: path("M5.75 8.5v4.25a6.25 8.5 0 0 0 12.5 0V8.5");
}

.jfl86sb5a {
  d: path("M10.75 8.5v4.25a1.25 3.5 0 0 0 2.5 0V8.5");
}

</style>

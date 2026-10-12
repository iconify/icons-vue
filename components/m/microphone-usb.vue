<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="rbcy4lb9e"/><path class="zh69h04cv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:microphone-usb" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rbcy4lb9e {
  width: 7.5px;
  height: 12.25px;
  x: 8.25px;
  y: 2.75px;
  rx: 3.75px;
}

.zh69h04cv {
  d: path("M8.25 7h3.25m-3.25 3h3.25m.5 5v3.5l-4.5 2.75M12 18.5l4.5 2.75");
}

</style>

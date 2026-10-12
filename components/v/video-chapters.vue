<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="mbm1s8bmi"/><path class="ecy2xpbdc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:video-chapters" /></template>
<style>
.ecy2xpbdc {
  d: path("m10.86 7.59l2.78 1.57q.61.34 0 .68l-2.78 1.57q-.61.34-.61-.36v-3.1q0-.7.61-.36M2.75 19.75h4.5m3 0h4m3 0h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mbm1s8bmi {
  width: 18.5px;
  height: 11.5px;
  x: 2.75px;
  y: 3.75px;
  rx: 2.5px;
}

</style>

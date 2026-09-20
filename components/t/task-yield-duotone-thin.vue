<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sno_8lb8f"/><path class="qvqi41cih"/><path class="av8tk7b8g"/><path class="p1-zbab-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:task-yield-duotone-thin" /></template>
<style>
.av8tk7b8g {
  d: path("m10 14 4.5 -4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p1-zbab-s {
  d: path("M12 6.5A2.5 2.5 0 0 1 14.5 4h4A2.5 2.5 0 0 1 21 6.5 2.5 2.5 0 0 1 18.5 9h-4A2.5 2.5 0 0 1 12 6.5");
}

.qvqi41cih {
  d: path("M8.69 13.37a4 4 0 1 1 -3.38 0");
}

.sno_8lb8f {
  fill: currentColor;
  d: path("M12 6.5A2.5 2.5 0 0 1 14.5 4h4A2.5 2.5 0 0 1 21 6.5 2.5 2.5 0 0 1 18.5 9h-4A2.5 2.5 0 0 1 12 6.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

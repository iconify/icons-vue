<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vtubo5bar"/><rect class="i4g8qib9k"/><path class="s39pugu1z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shop-awning" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i4g8qib9k {
  width: 10.5px;
  height: 6.75px;
  x: 6.75px;
  y: 14.5px;
  rx: 1.5px;
}

.s39pugu1z {
  d: path("M9.75 17.75h4.5");
}

.vtubo5bar {
  d: path("M6.8 3.75h10.4a1.5 1.5 0 0 1 1.24.65l2.6 3.8a1.5 1.5 0 0 1 .21.8a2.31 2.31 0 0 1-4.63 0A2.31 2.31 0 0 1 12 9a2.31 2.31 0 0 1-4.63 0a2.31 2.31 0 0 1-4.62 0v-.5a1.5 1.5 0 0 1 .26-.8l2.55-3.3a1.5 1.5 0 0 1 1.24-.65m2.95 0L7.37 9M12 3.75V9m2.25-5.25L16.62 9m-6.93 2.3v3.2m4.62-3.2v3.2");
}

</style>

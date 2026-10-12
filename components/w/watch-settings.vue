<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="xafv9k1ml"/><path class="j8uz70oyg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:watch-settings" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j8uz70oyg {
  d: path("m8.75 6.25l.5-3.5h5.5l.5 3.5m-6.5 11.5l.5 3.5h5.5l.5-3.5M12 9.25V12l1.75 1.25");
}

.xafv9k1ml {
  width: 12.5px;
  height: 11.5px;
  x: 5.75px;
  y: 6.25px;
  rx: 3px;
}

</style>

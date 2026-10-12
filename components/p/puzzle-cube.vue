<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zfw-jhbdp"/><path class="i3-jvr20i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:puzzle-cube" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i3-jvr20i {
  d: path("M4.25 7.92L12 12.25l7.75-4.33M12 12.25v8.4M8.52 5.55l6.96 3.9m0-3.9l-6.96 3.9");
}

.zfw-jhbdp {
  d: path("m13.31 3.48l5.88 3.29Q20.5 7.5 20.5 9v6q0 1.5-1.31 2.23l-5.88 3.29q-1.31.73-2.62 0l-5.88-3.29Q3.5 16.5 3.5 15V9q0-1.5 1.31-2.23l5.88-3.29q1.31-.73 2.62 0");
}

</style>

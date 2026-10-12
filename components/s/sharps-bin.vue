<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="c2qenibxs"/><path class="p67h13bgz"/><path class="anwx3v9er"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sharps-bin" /></template>
<style>
.anwx3v9er {
  d: path("m12.31 14.01l2.38 3.98q.31.51-.29.51H9.6q-.6 0-.29-.51l2.38-3.98q.31-.51.62 0M12 2.75v4");
}

.c2qenibxs {
  width: 16.5px;
  height: 3px;
  x: 3.75px;
  y: 6.75px;
  rx: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p67h13bgz {
  d: path("M6.75 9.75h10.5q1.5 0 1.37 1.49l-.74 8.52q-.13 1.49-1.63 1.49h-8.5q-1.5 0-1.63-1.49l-.74-8.52q-.13-1.49 1.37-1.49");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="y3v_xpb9z"/><circle class="fwf1xiw5o"/><circle class="aez0w84lj"/><path class="gc_8f121e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:skull-face-sharp" /></template>
<style>
.aez0w84lj {
  cx: 14.75px;
  cy: 10.25px;
  r: 1.75px;
}

.fwf1xiw5o {
  cx: 9.25px;
  cy: 10.25px;
  r: 1.75px;
}

.gc_8f121e {
  d: path("M12 13v1m-1.5 4v3.25m3-3.25v3.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y3v_xpb9z {
  d: path("M12 2.75c4.4 0 7.75 3 7.75 7.25c0 2.4-1 4.2-2.75 5.25v6H7v-6C5.25 14.2 4.25 12.4 4.25 10c0-4.25 3.35-7.25 7.75-7.25Z");
}

</style>

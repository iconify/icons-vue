<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f4ari4irz"/><rect class="dwn7dbctf"/><path class="mr1wmnbeh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ring-light" /></template>
<style>
.dwn7dbctf {
  width: 2.5px;
  height: 3.5px;
  x: 10.75px;
  y: 8px;
  rx: 0.75px;
}

.f4ari4irz {
  d: path("M19 9.75a7 7 0 1 1-14 0a7 7 0 1 1 14 0m-2.5 0a4.5 4.5 0 1 1-9 0a4.5 4.5 0 1 1 9 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mr1wmnbeh {
  d: path("M12 16.75v4.5m-3.5 0h7");
}

</style>

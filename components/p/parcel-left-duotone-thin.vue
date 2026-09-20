<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s9i-unr8j"/><path class="zrvo9u_3y"/><path class="tla8vyn6c"/><path class="rkhcgsbdl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:parcel-left-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rkhcgsbdl {
  d: path("M3 19h18");
}

.s9i-unr8j {
  fill: currentColor;
  d: path("M6 7v8h12V7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.tla8vyn6c {
  d: path("M12 7v8");
}

.zrvo9u_3y {
  d: path("M6 7v8h12V7Z");
}

</style>

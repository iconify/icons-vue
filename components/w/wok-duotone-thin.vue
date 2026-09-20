<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zev6zlbze"/><path class="vt8fxebuz"/><path class="q3b6j7bvq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wok-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q3b6j7bvq {
  d: path("M20 10c2 0 2 -4 -1 -4");
}

.vt8fxebuz {
  d: path("M4 10h16l-6 6h-4Z");
}

.zev6zlbze {
  fill: currentColor;
  d: path("M4 10h16l-6 6h-4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

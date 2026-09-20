<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mft5sm3ri"/><path class="e4rbzsbiw"/><path class="sg8usjbiz"/><path class="u2vvzw7_k"/><path class="wuk2mlziz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mushroom-duotone-thin" /></template>
<style>
.e4rbzsbiw {
  d: path("M3 11a9 9 0 0 1 18 0Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mft5sm3ri {
  fill: currentColor;
  d: path("M3 11a9 9 0 0 1 18 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.sg8usjbiz {
  d: path("M9 13v6");
}

.u2vvzw7_k {
  d: path("M15 13v6");
}

.wuk2mlziz {
  d: path("M7 19h10");
}

</style>

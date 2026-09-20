<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hsqp64b2e"/><path class="eua7f7bfo"/><path class="t9l7d0eki"/><path class="i6lzm3bun"/><path class="awo9bn4mw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:search-run-duotone-thin" /></template>
<style>
.awo9bn4mw {
  d: path("M16 8v8l4 -4Z");
}

.eua7f7bfo {
  fill: currentColor;
  d: path("M16 8v8l4 -4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hsqp64b2e {
  fill: currentColor;
  d: path("M4 10a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.i6lzm3bun {
  d: path("M5.5 13 3 15.5");
}

.t9l7d0eki {
  d: path("M4 10a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

</style>

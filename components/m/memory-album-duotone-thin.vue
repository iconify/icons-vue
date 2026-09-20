<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x5ujzyh2u"/><path class="yajmtkb-r"/><path class="uk66x15py"/><path class="wuvisubmw"/><path class="jxgkv6s4q"/><path class="sxbibil-o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:memory-album-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jxgkv6s4q {
  d: path("M11 8v8h6V8Z");
}

.sxbibil-o {
  d: path("m11 14 2 -2 3 3");
}

.uk66x15py {
  d: path("M4 3v18h16V3Z");
}

.wuvisubmw {
  d: path("M8 3v18");
}

.x5ujzyh2u {
  fill: currentColor;
  d: path("M4 3v18h16V3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.yajmtkb-r {
  fill: currentColor;
  d: path("M11 8v8h6V8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

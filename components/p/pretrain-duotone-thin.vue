<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lzjmz2eww"/><path class="ymudxkbnd"/><path class="jotk81b5q"/><path class="f4naz_w9a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pretrain-duotone-thin" /></template>
<style>
.f4naz_w9a {
  d: path("m9 5 3 3 3 -3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jotk81b5q {
  d: path("M12 2v6");
}

.lzjmz2eww {
  fill: currentColor;
  d: path("M14.5 11H17a3 3 0 0 1 3 3v4a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3v-3l4 -4h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ymudxkbnd {
  d: path("M14.5 11H17a3 3 0 0 1 3 3v4a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3v-3l4 -4h2.5");
}

</style>

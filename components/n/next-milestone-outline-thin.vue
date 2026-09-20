<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="crv4i00bu"/><path class="lulmb9b1a"/><path class="pr2xdw8hh"/><path class="a67_cn3fi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:next-milestone-outline-thin" /></template>
<style>
.a67_cn3fi {
  d: path("M13.5 7.5 16 10l-2.5 2.5");
}

.crv4i00bu {
  d: path("M4 3v18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lulmb9b1a {
  d: path("M4 4h16v12H4");
}

.pr2xdw8hh {
  d: path("M10.5 7.5 13 10l-2.5 2.5");
}

</style>

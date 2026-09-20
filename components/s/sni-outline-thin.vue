<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lyyswacbl"/><path class="uxsptjbvt"/><path class="druahpb2o"/><path class="d0m2g8bjt"/><path class="slu778b9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sni-outline-thin" /></template>
<style>
.d0m2g8bjt {
  d: path("m7 21 3 -3h7");
}

.druahpb2o {
  d: path("M6 11h9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lyyswacbl {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.slu778b9b {
  d: path("M18.5 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.uxsptjbvt {
  d: path("M6 7h12");
}

</style>

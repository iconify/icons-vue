<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aeyekmbly"/><path class="gnggw0bkv"/><path class="w3qv73i9r"/><path class="m7i92hb6f"/><path class="ve_htnadp"/><path class="b6rnmzrfq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:music-scale-outline-thin" /></template>
<style>
.aeyekmbly {
  d: path("M3 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.b6rnmzrfq {
  d: path("M19 11V5");
}

.gnggw0bkv {
  d: path("M7 19v-6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m7i92hb6f {
  d: path("M13 15V9");
}

.ve_htnadp {
  d: path("M15 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.w3qv73i9r {
  d: path("M9 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>

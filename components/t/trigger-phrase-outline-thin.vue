<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i9hgspbqe"/><path class="wb0w7r_ye"/><path class="w2flskbzg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:trigger-phrase-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i9hgspbqe {
  d: path("M6 4v3");
}

.w2flskbzg {
  d: path("m15 10 -4 4h3l-4 4");
}

.wb0w7r_ye {
  d: path("M9.5 4v3");
}

</style>

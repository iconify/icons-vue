<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="zohykibek"/><path class="kl5egs07h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:request-id-api-outline-thin" /></template>
<style>
.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kl5egs07h {
  d: path("M9.5 12.5 12 15l2.5 -2.5");
}

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

.zohykibek {
  d: path("M10 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>

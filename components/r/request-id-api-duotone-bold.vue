<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="tzxtpfb7v"/><path class="c1kziyotx"/><path class="hieqhxiaw"/><path class="a7jzobc5s"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="zohykibek"/><path class="kl5egs07h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:request-id-api-duotone-bold" /></template>
<style>
.a7jzobc5s {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9.5 12.5 12 15l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.c1kziyotx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.hieqhxiaw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kl5egs07h {
  d: path("M9.5 12.5 12 15l2.5 -2.5");
}

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tzxtpfb7v {
  fill: currentColor;
  d: path("M10 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zohykibek {
  d: path("M10 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>

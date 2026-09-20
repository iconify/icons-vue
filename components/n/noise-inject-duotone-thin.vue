<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="npenpvb6u"/><path class="ibuanu9pl"/><path class="t917aebob"/><path class="zml9_hk2z"/><path class="hf_gtezns"/><path class="tgth1rbuy"/><path class="lzdsnnb7v"/><path class="ydp7-vbsy"/><path class="rod9nhbdx"/><path class="xyj-l9cjp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:noise-inject-duotone-thin" /></template>
<style>
.hf_gtezns {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ibuanu9pl {
  fill: currentColor;
  d: path("M11 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.lzdsnnb7v {
  d: path("M11 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.npenpvb6u {
  fill: currentColor;
  d: path("M6 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rod9nhbdx {
  d: path("m10 12.5 2 2 2 -2");
}

.t917aebob {
  fill: currentColor;
  d: path("M16 4.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.tgth1rbuy {
  d: path("M6 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.xyj-l9cjp {
  d: path("M3 18h18");
}

.ydp7-vbsy {
  d: path("M16 4.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.zml9_hk2z {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10 12.5 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="uwosf5b9n"/><path class="xhjwhszyc"/><path class="slm2u3bjw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:symfonium-note" /></template>
<style>
.slm2u3bjw {
  d: path("M34.246 4.5h.028a3.207 3.207 0 1 1 0 6.414h-.028");
}

.uwosf5b9n {
  d: path("M26.305 35.525v.082a7.893 7.893 0 1 1-7.893-7.893c1.692 0 3.34.543 4.699 1.55M34.325 4.516H25.28a2.037 2.037 0 0 0-2.037 2.037l.011 22.802");
}

.xhjwhszyc {
  d: path("M34.44 10.909h-6.098a2.037 2.037 0 0 0-2.037 2.037v22.679");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

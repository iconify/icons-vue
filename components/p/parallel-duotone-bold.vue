<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rzdonbckf"/><path class="f7f52fb8i"/><path class="boqmo37co"/><path class="amid48b6f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:parallel-duotone-bold" /></template>
<style>
.amid48b6f {
  d: path("m8 12 4 4h9");
}

.boqmo37co {
  d: path("M3 12h5l4 -4h9");
}

.f7f52fb8i {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m8 12 4 4h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rzdonbckf {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12h5l4 -4h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ehzfylb8o"/><path class="mgt26xbkp"/><path class="okud9xj_d"/><path class="wg8_ddc1f"/><path class="dxs1ifmed"/><path class="vjdmi0bfh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rollback-deploy-duotone-bold" /></template>
<style>
.dxs1ifmed {
  d: path("M8.5 9.5 6 12l2.5 2.5");
}

.ehzfylb8o {
  fill: currentColor;
  d: path("M2 7a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.mgt26xbkp {
  fill: currentColor;
  d: path("M14 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.okud9xj_d {
  d: path("M2 7a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vjdmi0bfh {
  d: path("M14 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.wg8_ddc1f {
  d: path("M6 12h6");
}

</style>

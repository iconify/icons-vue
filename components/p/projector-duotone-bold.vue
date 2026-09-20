<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pwnv3b5fk"/><path class="vn39u9btx"/><path class="vvyrl1k7r"/><path class="na074v-mn"/><path class="j49v8ng1j"/><path class="q1ae0k4gd"/><path class="er1zo2e1s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:projector-duotone-bold" /></template>
<style>
.er1zo2e1s {
  d: path("M20 4v17");
}

.j49v8ng1j {
  d: path("m14 9 4 -4");
}

.na074v-mn {
  d: path("M6 12.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.pwnv3b5fk {
  fill: currentColor;
  d: path("M2 10a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.q1ae0k4gd {
  d: path("m14 16 4 4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vn39u9btx {
  fill: currentColor;
  d: path("M6 12.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.vvyrl1k7r {
  d: path("M2 10a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>

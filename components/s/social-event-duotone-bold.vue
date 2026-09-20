<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vfgkudb8l"/><path class="w29n56brn"/><path class="qsaixhm4f"/><path class="nca7pq6lm"/><path class="qcx0_7byx"/><path class="dwj8i8b7i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:social-event-duotone-bold" /></template>
<style>
.dwj8i8b7i {
  d: path("M6 10c1 2 3 2 4 0 1 2 3 2 4 0 1 2 3 2 4 0");
}

.nca7pq6lm {
  d: path("m4 10 8 -8 8 8");
}

.qcx0_7byx {
  d: path("M6 10v10h12V10");
}

.qsaixhm4f {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 10c1 2 3 2 4 0 1 2 3 2 4 0 1 2 3 2 4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vfgkudb8l {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m4 10 8 -8 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w29n56brn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 10v10h12V10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lqcp5xb1v"/><path class="t3vzob-fn"/><path class="md05zk1ss"/><path class="at7ws5bbl"/><path class="rm8glg-ni"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:trace-waterfall-outline-regular" /></template>
<style>
.at7ws5bbl {
  d: path("M9.5 12h5");
}

.lqcp5xb1v {
  d: path("M4 3h16");
}

.md05zk1ss {
  d: path("M7 9h5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rm8glg-ni {
  d: path("M12 15h5");
}

.t3vzob-fn {
  d: path("M2 12a6 6 0 0 1 6 -6h8a6 6 0 0 1 6 6 6 6 0 0 1 -6 6H8a6 6 0 0 1 -6 -6");
}

</style>

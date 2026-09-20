<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bpciasb2z"/><path class="c11_n0b6s"/><path class="k3juqlbuw"/><path class="r1ix196dy"/><path class="lit20acsf"/><path class="u41hfsjfh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:order-history-outline-thin" /></template>
<style>
.bpciasb2z {
  d: path("M3 5.5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.c11_n0b6s {
  d: path("M6.5 19.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k3juqlbuw {
  d: path("M15.5 19.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.lit20acsf {
  d: path("M12 7.5v3");
}

.r1ix196dy {
  d: path("M9 10.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.u41hfsjfh {
  d: path("M12 10.5h2.5");
}

</style>

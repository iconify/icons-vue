<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nykd-mj4n"/><path class="ynpow9obf"/><path class="ot2c6rnyg"/><path class="uzrj-lb1g"/><path class="pohupsbfv"/><path class="f99n1fbkg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mental-health-first-aid-duotone-thin" /></template>
<style>
.f99n1fbkg {
  d: path("M16 7h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nykd-mj4n {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 21v-3c-1.5 -1.5 -2 -4 -2 -6.5a6 6 0 0 1 12 -1c0 1.5 1.5 2 1.5 3s-1 1 -1.5 1V17a1.5 1.5 0 0 1 -1.5 1.5H11V21");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ot2c6rnyg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 7h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pohupsbfv {
  d: path("M19 4v6");
}

.uzrj-lb1g {
  d: path("M5 21v-3c-1.5 -1.5 -2 -4 -2 -6.5a6 6 0 0 1 12 -1c0 1.5 1.5 2 1.5 3s-1 1 -1.5 1V17a1.5 1.5 0 0 1 -1.5 1.5H11V21");
}

.ynpow9obf {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 4v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

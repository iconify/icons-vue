<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ofidmqbqd"/><circle class="c9bd5qgta"/><circle class="b5yof9bmt"/><path class="sr71kjbeu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:phone-conference" /></template>
<style>
.b5yof9bmt {
  cx: 18.75px;
  cy: 4.25px;
  r: 1.25px;
}

.c9bd5qgta {
  cx: 14.5px;
  cy: 4.25px;
  r: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ofidmqbqd {
  d: path("M5.6 3.25h2.6a1 1 0 0 1 .95.68l1.1 3.3A1 1 0 0 1 10 8.25l-1.6 1.6a12.5 12.5 0 0 0 5.75 5.75l1.6-1.6a1 1 0 0 1 1.02-.25l3.3 1.1a1 1 0 0 1 .68.95v2.6a2.35 2.35 0 0 1-2.35 2.35c-8.3 0-15.15-6.85-15.15-15.15A2.35 2.35 0 0 1 5.6 3.25");
}

.sr71kjbeu {
  d: path("M12.25 9.5c.3-1.4 1.1-2.25 2.25-2.25s1.95.85 2.25 2.25m-.25 0c.3-1.4 1.1-2.25 2.25-2.25S20.7 8.1 21 9.5");
}

</style>

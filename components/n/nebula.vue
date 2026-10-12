<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="ks52xhbhk"/><path class="tiow9zmqh"/><path class="c9oiszudw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:nebula" /></template>
<style>
.c9oiszudw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19.5 3.5h.01");
}

.ks52xhbhk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.09 9.82l.57-1.14Q6 6 8.5 5.38q2.5-.63 4.5.5q2 1.12 4.25 1.5q2.25.37 3.13 3q.87 2.62-.77 5.13l-.47.73q-1.64 2.51-4.61 2.97l-.56.08q-2.97.46-5.76-.63l-.17-.07Q5.25 17.5 4 15t.09-5.18");
}

.tiow9zmqh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 8.5q.48 3.52 4 4q-3.52.48-4 4q-.48-3.52-4-4q3.52-.48 4-4");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

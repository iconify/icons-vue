<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="ug9f204qh"/><path class="n2802jk1h"/><path class="vx1dezr1q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mansion" /></template>
<style>
.n2802jk1h {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.25 14h.01m-.01 4h.01m13.49-4h.01m-.01 4h.01M12 9h.01");
}

.ug9f204qh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.65V12.1q0-.6.39-1.06l.72-.83q.39-.46.99-.46H6.9q.6 0 1.02-.42l3.66-3.66q.42-.42.84 0l3.66 3.66q.42.42 1.02.42h2.05q.6 0 .99.46l.72.83q.39.46.39 1.06v8.55q0 .6-.6.6H3.35q-.6 0-.6-.6");
}

.vx1dezr1q {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 12.75v4.5m5-4.5v4.5m-4 4v-3a1.5 1.5 0 0 1 3 0v3");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

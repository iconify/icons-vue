<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="vexmik5ab"/><path class="zrnuaslnh"/><path class="qutk18-3b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:school-building" /></template>
<style>
.qutk18-3b {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 21.25V18h3v3.25m-8.25-5.5h1.5m10.5 0h1.5");
}

.vexmik5ab {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.5v-7.75q0-.75.75-.75h4.25q.75 0 .75-.75v-1.5q0-.75.57-1.24l2.36-2.02q.57-.49 1.14 0l2.36 2.02q.57.49.57 1.24v1.5q0 .75.75.75h4.25q.75 0 .75.75v7.75q0 .75-.75.75h-17q-.75 0-.75-.75M12 6V2.75l3 1.1l-3 1.1");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zrnuaslnh {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 10.5h.01");
}

</style>

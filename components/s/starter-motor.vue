<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="h2g64_iqg"/><path class="hkdk0ub8j"/><rect class="ro-lkvsdn"/><path class="ey13_kb4r"/><path class="y-k810yhc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:starter-motor" /></template>
<style>
.ey13_kb4r {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.5 15h2.25m2.34-1.95l-.01-.37q-.02-.39.38-.39h.08q.4 0 .38.39l-.01.37q-.01.4.33.6l.06.03q.34.2.68-.01l.31-.19q.34-.22.54.13l.04.07q.2.34-.15.53l-.33.17q-.35.19-.35.59v.06q0 .4.35.59l.33.17q.35.19.15.53l-.04.07q-.2.35-.54.13l-.31-.19q-.34-.21-.68-.01l-.06.03q-.34.2-.33.6l.01.37q.02.39-.38.39h-.08q-.4 0-.38-.39l.01-.37q.01-.4-.33-.6l-.06-.03q-.34-.2-.68.01l-.31.19q-.34.22-.54-.13l-.04-.07q-.2-.34.15-.53l.33-.17q.35-.19.35-.59v-.06q0-.4-.35-.59l-.33-.17q-.35-.19-.15-.53l.04-.07q.2-.35.54-.13l.31.19q.34.21.68.01l.06-.03q.34-.2.33-.6");
}

.h2g64_iqg {
  width: 10.75px;
  height: 8px;
  x: 2.75px;
  y: 11px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.hkdk0ub8j {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 11v8");
}

.ro-lkvsdn {
  width: 8.25px;
  height: 3.75px;
  x: 4.75px;
  y: 5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.25px;
}

.y-k810yhc {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.5 15h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

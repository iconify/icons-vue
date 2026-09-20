<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="abnm6smsv"/><path class="cen-7fbaj"/><path class="d2st3ss-c"/><path class="l1jjkky7x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sla-outline-regular" /></template>
<style>
.abnm6smsv {
  d: path("M13 3H6v18h12V8");
}

.cen-7fbaj {
  d: path("M8.24 13.63a4 4 0 0 1 7.5 0");
}

.d2st3ss-c {
  d: path("m12 15 2.5 -2.5");
}

.l1jjkky7x {
  d: path("M8 18h8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

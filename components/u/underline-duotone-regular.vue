<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fha5-ubus"/><path class="qnt_uubje"/><path class="ic_pehd5a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:underline-duotone-regular" /></template>
<style>
.fha5-ubus {
  fill: currentColor;
  d: path("M5 7a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ic_pehd5a {
  d: path("M3 17h18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qnt_uubje {
  d: path("M5 7a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

</style>

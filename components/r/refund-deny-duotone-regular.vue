<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ots31sbwo"/><path class="jd_dotbnq"/><path class="o7jy28bce"/><path class="cpsm-qevf"/><path class="c0xzggwkx"/><path class="hatc3g_gl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:refund-deny-duotone-regular" /></template>
<style>
.c0xzggwkx {
  d: path("m13.5 8 4 4");
}

.cpsm-qevf {
  d: path("M9 7.5 6.5 10 9 12.5");
}

.hatc3g_gl {
  d: path("m17.5 8 -4 4");
}

.jd_dotbnq {
  d: path("M6 2h12a2 2 0 0 1 2 2v15l-2 -2 -2 2 -2 -2 -2 2 -2 -2 -2 2 -2 -2 -2 2V4a2 2 0 0 1 2 -2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o7jy28bce {
  d: path("M6.5 10H11");
}

.ots31sbwo {
  fill: currentColor;
  d: path("M6 2h12a2 2 0 0 1 2 2v15l-2 -2 -2 2 -2 -2 -2 2 -2 -2 -2 2 -2 -2 -2 2V4a2 2 0 0 1 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

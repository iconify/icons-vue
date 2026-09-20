<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m_6avib3e"/><path class="ib0uz7xmw"/><path class="jhjyblmry"/><path class="g2aaxgb5s"/><path class="exre5jj_d"/><path class="b9e7op5tz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:usb-outline-regular" /></template>
<style>
.b9e7op5tz {
  d: path("M3 7.5h4.5V12H3Z");
}

.exre5jj_d {
  d: path("m12 15 -4.5 -4.5");
}

.g2aaxgb5s {
  d: path("M15.5 6.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.ib0uz7xmw {
  d: path("M10 20a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.jhjyblmry {
  d: path("m12 12 4.5 -4.5");
}

.m_6avib3e {
  d: path("M12 3v17");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

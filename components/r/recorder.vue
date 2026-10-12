<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="tlad0-fsj"/><path class="ovzd_n1ad"/><path class="p9jcxcb3f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:recorder" /></template>
<style>
.ovzd_n1ad {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 6h2m-2 3h2q.75 0 .75.75v7q0 .75.19 1.47l.62 2.31q.19.72-.56.72h-4q-.75 0-.56-.72l.62-2.31q.19-.72.19-1.47v-7q0-.75.75-.75");
}

.p9jcxcb3f {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01M12 15h.01");
}

.tlad0-fsj {
  width: 5px;
  height: 6.25px;
  x: 9.5px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 0.75px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

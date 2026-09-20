<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nozx3gb_o"/><path class="yxn1e3bps"/><path class="q-g5v7b1p"/><path class="a2rsdhb4f"/><path class="ic_pehd5a"/><path class="edx-aqbqz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tls-terminate-duotone-bold" /></template>
<style>
.a2rsdhb4f {
  d: path("M12 14v3");
}

.edx-aqbqz {
  d: path("m18 20 3 -3 -3 -3");
}

.ic_pehd5a {
  d: path("M3 17h18");
}

.nozx3gb_o {
  fill: currentColor;
  d: path("M6 7a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.q-g5v7b1p {
  d: path("M7.5 5a2.5 2.5 0 0 1 5 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.yxn1e3bps {
  d: path("M6 7a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

</style>

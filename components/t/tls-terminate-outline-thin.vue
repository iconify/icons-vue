<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yxn1e3bps"/><path class="q-g5v7b1p"/><path class="a2rsdhb4f"/><path class="ic_pehd5a"/><path class="edx-aqbqz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tls-terminate-outline-thin" /></template>
<style>
.a2rsdhb4f {
  d: path("M12 14v3");
}

.edx-aqbqz {
  d: path("m18 20 3 -3 -3 -3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ic_pehd5a {
  d: path("M3 17h18");
}

.q-g5v7b1p {
  d: path("M7.5 5a2.5 2.5 0 0 1 5 0");
}

.yxn1e3bps {
  d: path("M6 7a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

</style>

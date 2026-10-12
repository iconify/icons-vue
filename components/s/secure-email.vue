<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="z-s-1_qmj"/><path class="wmbed2cai"/><path class="o40ix-bpd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:secure-email" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o40ix-bpd {
  d: path("M16 16.75L17.25 18l2-2.25");
}

.wmbed2cai {
  d: path("m2.75 6.5l6.75 5l6.75-5m1.67 6.38l2.41.99q.92.38.92 1.38v1.06q0 1-.73 1.68l-2.79 2.58q-.73.68-1.46 0l-2.79-2.58q-.73-.68-.73-1.68v-1.06q0-1 .92-1.38l2.41-.99q.92-.38 1.84 0");
}

.z-s-1_qmj {
  width: 13.5px;
  height: 12px;
  x: 2.75px;
  y: 4.75px;
  rx: 2px;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b4h2t8jbx"/><path class="dum2vjb4o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:stevenson-screen" /></template>
<style>
.b4h2t8jbx {
  d: path("M7.5 5h9A1.5 1.5 0 0 1 18 6.5v6a1.5 1.5 0 0 1-1.5 1.5h-9A1.5 1.5 0 0 1 6 12.5v-6A1.5 1.5 0 0 1 7.5 5");
}

.dum2vjb4o {
  d: path("m8.25 3.75l3.276-1.092a1.5 1.5 0 0 1 .948 0L15.75 3.75A.641.641 0 0 1 15.547 5H8.453a.641.641 0 0 1-.203-1.25M6 8h12M6 11h12M8 14v7.5m8-7.5v7.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b14_v19hm"/><circle class="ab1300b9n"/><path class="frsaaq3rt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:school" /></template>
<style>
.ab1300b9n {
  cx: 12px;
  cy: 10.5px;
  r: 1.25px;
}

.b14_v19hm {
  d: path("M3 20v-9q0-1 .87-1.49l7.26-4.02q.87-.49 1.74 0l7.26 4.02Q21 10 21 11v9q0 1-1 1H4q-1 0-1-1m9-15V2.75l3.75 1l-3.75 1");
}

.frsaaq3rt {
  d: path("M10 21v-6h4v6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

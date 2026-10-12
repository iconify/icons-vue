<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jhwy_m4sr"/><path class="u3ogxcc_l"/><path class="sbzrimxqj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:whiteboard-marker" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jhwy_m4sr {
  d: path("m12.21 9.66l2.13 2.13q1.06 1.06 2.12 0l3-3.01q1.06-1.06 0-2.12l-2.12-2.12q-1.06-1.06-2.12 0l-3.01 3q-1.06 1.06 0 2.12");
}

.sbzrimxqj {
  d: path("m5.14 17.08l1.78 1.78q.35.35 0 .7l-1.07 1.07q-.35.35-.78.09l-1.79-1.07q-.43-.26-.14-.66l1.36-1.86q.29-.4.64-.05");
}

.u3ogxcc_l {
  d: path("m4.79 16.73l2.48 2.48q.88.88 1.76 0l5.49-5.48q.88-.88 0-1.76l-2.49-2.49q-.88-.88-1.76 0l-5.48 5.49q-.88.88 0 1.76");
}

</style>

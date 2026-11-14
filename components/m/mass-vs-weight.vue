<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="txsiqdbai"/><path class="oml8slv9v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mass-vs-weight" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oml8slv9v {
  d: path("M5.507 9.5h.986a1.75 1.75 0 0 1 1.731 1.49l.975 6.5a1.75 1.75 0 0 1-1.731 2.01H4.532a1.75 1.75 0 0 1-1.731-2.01l.975-6.5A1.75 1.75 0 0 1 5.507 9.5M16.25 5v14.5m-3 0h6M12.5 7H20m-7.5 0v3.5m-1.5 0a1.5 1.5 0 0 0 3 0ZM20 7v3.5m-1.5 0a1.5 1.5 0 0 0 3 0Z");
}

.txsiqdbai {
  d: path("M3.5 7a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>

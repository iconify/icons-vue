<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="veshckt1j"/><path class="qjx50y1aw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:marble-stone" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qjx50y1aw {
  d: path("M2.5 11c3.5-2 5.5 2.5 9 1c2.5-1 4.5-4.5 7.75-5.75M9.75 19.5C11 16.5 13.5 17 16 15c1.5-1.25 3-1.5 5-2");
}

.veshckt1j {
  d: path("m6.061 4.912l10.13-.845a1.75 1.75 0 0 1 1.383.507l3.331 3.331a1.75 1.75 0 0 1 .502 1.431l-.802 7.218a1.75 1.75 0 0 1-.957 1.372l-3.706 1.853a1.75 1.75 0 0 1-.934.178l-9.684-.842a1.75 1.75 0 0 1-1.569-1.421l-1.159-6.181a1.75 1.75 0 0 1 .105-.995l1.89-4.536a1.75 1.75 0 0 1 1.47-1.07");
}

</style>

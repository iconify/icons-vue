<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ns0c7bbfw"/><path class="cxuxqq_-d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:monitor-cog" /></template>
<style>
.cxuxqq_-d {
  d: path("M11.398 7.32za.546.546 0 0 1 .546-.519h.112a.546.546 0 0 1 .546.519a.96.96 0 0 0 .476.779l.029.017a.96.96 0 0 0 .913.023a.546.546 0 0 1 .722.213l.056.097a.546.546 0 0 1-.177.732a.96.96 0 0 0-.436.802v.034a.96.96 0 0 0 .436.802a.546.546 0 0 1 .177.732l-.056.097a.546.546 0 0 1-.722.213a.96.96 0 0 0-.913.023l-.029.017a.96.96 0 0 0-.476.779a.546.546 0 0 1-.546.519h-.112a.546.546 0 0 1-.546-.519a.96.96 0 0 0-.476-.779l-.029-.017a.96.96 0 0 0-.913-.023a.546.546 0 0 1-.722-.213l-.056-.097a.546.546 0 0 1 .177-.732a.96.96 0 0 0 .436-.802v-.034a.96.96 0 0 0-.436-.802a.546.546 0 0 1-.177-.732l.056-.097a.546.546 0 0 1 .722-.213a.96.96 0 0 0 .913-.023l.029-.017a.96.96 0 0 0 .476-.779");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ns0c7bbfw {
  d: path("M6.875 3.5h10.25A4.375 4.375 0 0 1 21.5 7.875v4.25a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 12.125v-4.25A4.375 4.375 0 0 1 6.875 3.5M12 16.5v4m-4 0h8");
}

</style>

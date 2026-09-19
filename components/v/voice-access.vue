<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="o99h-3bwa"/><path class="qn0570bix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:voice-access" /></template>
<style>
.o99h-3bwa {
  cx: 14.355px;
  cy: 19.496px;
  r: 4.934px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qn0570bix {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.734 33.276v1.69a1.64 1.64 0 0 1-1.645 1.645H6.145A1.64 1.64 0 0 1 4.5 34.966v-1.69c2.159-7.02 18.973-5.817 20.234 0m.524-12.399v5.032m4.561-9.697v14.363M34.38 11.39v24.007m9.12-14.52v5.032m-4.56-9.697v14.363");
}

</style>

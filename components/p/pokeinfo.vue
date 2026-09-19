<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="lussfccyh"/><path class="tlrsm2but"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pokeinfo" /></template>
<style>
.lussfccyh {
  cx: 13.229px;
  cy: 24px;
  r: 3.322px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tlrsm2but {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.6 21.97C3.62 11.05 12.81 2.5 24 2.5s20.38 8.55 21.4 19.47H23.53c-.91-3.71-4.26-6.47-8.25-6.47c-4 0-7.34 2.76-8.25 6.47zm4.43 4.06H2.6C3.62 36.95 12.81 45.5 24 45.5s20.38-8.55 21.4-19.47H23.53c-.91 3.71-4.26 6.47-8.25 6.47c-4 0-7.34-2.76-8.25-6.47");
}

</style>

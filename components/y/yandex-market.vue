<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="ogjopgb5g"/><path class="v9rms-_kc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yandex-market" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ogjopgb5g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m6.14 35.97l7.4-9.82l-1.44 10.18l7.89 2.72l9.6-15.34c-.43 2.87-1.15 9.46 5.16 11.47c3.13.95 6.137-.178 8.907-2.458");
}

.v9rms-_kc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.093 19.814c-3.07 4.63-6.024 7.896-7.604 7.486c-2.72-.72-.28-9.46 1.29-15.05v-.15l-8.74-3.01l-10.46 17.06l1.43-9.32l-7.6-2.58L2.883 28.063");
}

</style>

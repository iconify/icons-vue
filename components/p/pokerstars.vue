<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hcj0aab0d"/><path class="wo3p5ubuv"/><path class="jpntqiiao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pokerstars" /></template>
<style>
.hcj0aab0d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5a144 144 0 0 0-10.435 10.319c-3.996 4.586-6.52 8.76-6.804 13.613a7.767 7.767 0 0 0 6.49 8.24c3.001.333 6.248-.671 7.454-2.474s2.423-1.927 2.204.107s-1.737 7.288-6.533 9.195H24");
}

.jpntqiiao {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5a144 144 0 0 1 10.435 10.319c3.996 4.586 6.52 8.76 6.804 13.613a7.767 7.767 0 0 1-6.489 8.24c-3.001.333-6.248-.671-7.454-2.474s-2.424-1.927-2.204.107s1.736 7.288 6.532 9.195H24");
}

.wo3p5ubuv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 13.862l1.972 6.114l6.422-.014l-5.204 3.765l1.998 6.106L24 26.045l-5.188 3.788l1.998-6.106l-5.205-3.765l6.423.014Z");
}

</style>

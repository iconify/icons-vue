<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p18bcjbgf"/><path class="u3o9pibti"/><path class="xlx868rnn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stored-procedure" /></template>
<style>
.p18bcjbgf {
  d: path("M3.5 5.5a7 2.5 0 1 0 14 0a7 2.5 0 1 0-14 0Z");
}

.u3o9pibti {
  d: path("M3.5 5.5v12q0 .061.008.123q.009.061.026.122t.042.122t.059.121t.075.119t.091.119q.05.058.108.116t.124.115t.139.112t.155.109t.169.107q.088.053.184.104q.095.051.198.1q.102.05.211.097t.224.093t.237.089t.249.084t.26.081q.133.038.271.075t.281.071t.29.065q.148.032.299.061q.152.029.307.055t.314.05t.321.044t.326.038t.331.033t.335.027t.339.021t.341.015t.343.009q.171.003.343.003q.873 0 1.72-.077m5.28-7.881V5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xlx868rnn {
  d: path("M3.5 11.5q0 .061.008.123q.009.061.026.122t.042.122t.059.121t.075.119t.091.119q.05.058.108.116t.124.115q.066.056.139.112q.074.055.155.109q.081.055.169.107q.088.053.184.104q.095.051.198.1q.102.05.211.097t.224.093q.116.045.237.089q.122.043.249.084t.26.081q.133.038.271.075t.281.071t.29.065q.148.032.299.061q.152.029.307.055t.314.05q.159.023.321.044t.326.038t.331.033t.335.027q.169.012.339.021t.341.015t.343.009q.171.003.343.003q1.614 0 3.065-.252m3.808-1.775q.127-.234.127-.473m-.128 4.339l.052-1.038h1.152l.052 1.038l.929.537l.925-.474l.576.997l-.873.564v1.074l.873.564l-.576.997l-.925-.474l-.929.537l-.052 1.038h-1.152l-.052-1.038l-.929-.537l-.925.474l-.576-.997l.873-.564v-1.074l-.873-.564l.576-.997l.925.474Z");
}

</style>

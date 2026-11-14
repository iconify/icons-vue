<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k1rk9abnh"/><path class="t4obwcbfx"/><path class="cssr4zbrr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tax-coins" /></template>
<style>
.cssr4zbrr {
  d: path("M3.5 9.5a6.5 2.5 0 0 0 13 0m-13 4q0 .061.008.123q.008.061.023.122q.016.061.039.122q.024.061.055.121t.07.119t.085.119q.046.058.1.116t.115.115q.061.056.129.112q.068.055.144.109q.075.055.157.107q.082.053.17.104t.184.1q.095.05.196.097t.209.093q.107.045.22.089q.113.043.231.084t.241.081q.124.038.252.075t.261.071q.132.034.269.065q.137.032.278.061t.285.055t.292.05q.147.023.297.044t.303.038t.308.033t.311.027q.156.012.314.021t.317.015t.318.009T10 16q1.137 0 2.207-.149M15.5 21.5l6-6m-6.5.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m4.5 4.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k1rk9abnh {
  d: path("M3.5 5.5a6.5 2.5 0 1 0 13 0a6.5 2.5 0 1 0-13 0");
}

.t4obwcbfx {
  d: path("M3.5 5.5v12q0 .061.008.123q.008.061.023.122q.016.061.039.122q.024.061.055.121t.07.119t.085.119q.046.058.1.116t.115.115t.129.112t.144.109q.075.055.157.107q.082.053.17.104t.184.1q.095.05.196.097t.209.093t.22.089q.113.043.231.084t.241.081q.124.038.252.075t.261.071q.132.034.269.065q.137.032.278.061t.285.055t.292.05t.297.044q.15.021.303.038q.153.018.308.033q.154.015.311.027q.156.012.314.021t.317.015t.318.009T10 20q.906 0 1.777-.095q.872-.096 1.642-.279m3.081-7.422V5.5");
}

</style>

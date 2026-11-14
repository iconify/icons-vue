<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="inmrp7b-y"/><path class="us4s4f3ql"/><path class="gw2xxbbxt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:redis-cache" /></template>
<style>
.gw2xxbbxt {
  d: path("M2.5 10.5q0 .061.009.123q.009.061.027.122t.045.122t.063.121t.081.119t.098.119q.053.058.115.116t.133.115q.07.056.149.112q.079.055.166.109q.086.055.181.107q.095.053.197.104t.212.1t.226.097t.241.093t.254.089t.266.084q.137.042.279.081q.142.038.29.075t.301.071t.311.065q.158.032.321.061q.162.029.328.055q.167.026.337.05q.17.023.343.044t.35.038t.355.033t.359.027q.18.012.363.021q.182.009.365.015t.367.009T10 13q.772 0 1.528-.052q.756-.053 1.464-.156q.708-.102 1.338-.251q.631-.148 1.157-.337M17.75 14l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291l-2.057-1.082l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

.inmrp7b-y {
  d: path("M2.5 5a7.5 2.5 0 1 0 15 0a7.5 2.5 0 1 0-15 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.us4s4f3ql {
  d: path("M2.5 5v13q0 .061.009.123q.009.061.027.122t.045.122t.063.121t.081.119t.098.119q.053.058.115.116t.133.115t.149.112t.166.109q.086.055.181.107q.095.053.197.104t.212.1t.226.097t.241.093t.254.089t.266.084q.137.042.279.081q.142.038.29.075t.301.071t.311.065q.158.032.321.061q.162.029.328.055q.167.026.337.05q.17.023.343.044t.35.038q.176.018.355.033q.178.015.359.027q.18.012.363.021q.182.009.365.015t.367.009t.368.003q1.51 0 2.902-.195M17.5 8.273V5");
}

</style>

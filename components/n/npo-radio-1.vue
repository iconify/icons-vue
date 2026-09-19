<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(-45 16.963 16.78)" class="u_kdx-imy"/><path class="thvr-sbfl"/><rect transform="rotate(-45 13.251 20.492)" class="dmngckbhe"/><path class="rbs377uci"/><rect transform="rotate(-45 31.5 24)" class="fjjd_9blu"/><path class="n63nyrhvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:npo-radio-1" /></template>
<style>
.dmngckbhe {
  width: 3.246px;
  height: 4.305px;
  x: 11.628px;
  y: 18.34px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.04px;
}

.fjjd_9blu {
  width: 19.132px;
  height: 19.132px;
  x: 21.934px;
  y: 14.434px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.276px;
}

.n63nyrhvs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.5 28v-8");
}

.rbs377uci {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.73 21.263l3.45 3.444M24 30.028l-6.598 6.598a1.276 1.276 0 0 1-1.804 0L3.874 24.902a1.276 1.276 0 0 1 0-1.804l11.724-11.724a1.276 1.276 0 0 1 1.804 0L24 17.972");
}

.thvr-sbfl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.214 24.573l-2.308-2.308a1.04 1.04 0 0 0-1.47-.003l-.003.003l-.83.822a1.05 1.05 0 0 0 0 1.474l2.316 2.308");
}

.u_kdx-imy {
  width: 3.246px;
  height: 4.305px;
  x: 15.34px;
  y: 14.627px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.04px;
}

</style>

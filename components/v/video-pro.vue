<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bq9nviauj"/><rect class="yphj3obqd"/><path class="zlma_3hks"/><path class="ytb-27spb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:video-pro" /></template>
<style>
.bq9nviauj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.429 33.535H20.604V22.267h18.62l1.205 1.779zm0-9.489H43.5v9.489h-3.071zm.042 9.489H21.367v2.372H39.37zM16.982 23.029h3.622v10.505h-3.622zm-8.811-.614h6.524v11.543H8.171zm6.524 11.543l2.287-.423V23.029l-2.287-.614zm-9.39.763l2.866-.763V22.415l-2.866-.875zm8.345-21.555h4.829v6.806H13.65z");
}

.yphj3obqd {
  width: 9.15px;
  height: 5.648px;
  x: 4.5px;
  y: 12.093px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.824px;
  ry: 2.824px;
}

.ytb-27spb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m41.551 21.13l-2.089-1.497h-2.918m-15.94 11.946h6.983v-9.312M13.65 18.748h-3.157v-1.007m25.187.506h-17.2m21.949 5.799H27.587");
}

.zlma_3hks {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.479 16.442h16.069M21.53 18.247c-.21.8-.01 1.68.58 2.32l1.57 1.7m9.81-4.02l.01.03c.46.99.03 2.17-.98 2.62l-3.08 1.37m8.751 0l-3.643-5.825h4.716l2.287-1.666m0 6.354v-6.354l1.132 1.286a2.86 2.86 0 0 1 0 3.782z");
}

</style>

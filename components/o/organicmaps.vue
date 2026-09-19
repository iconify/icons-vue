<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wq64e8kke"/><path class="hpmmwt--i"/><path class="cf8kyhbfb"/><path class="szuqhzb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:organicmaps" /></template>
<style>
.cf8kyhbfb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.325 10.31c2.34-.733 4.779-1.093 5.553.396c1.36 2.611-2.444 8.147-7.825 11.621a39.4 39.4 0 0 1-11.36 4.875");
}

.hpmmwt--i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.585 27.67c-2.206.643-4.405.877-5.134-.522C5.092 24.536 8.896 19 14.276 15.526a39.4 39.4 0 0 1 11.36-4.875m7.417 11.677c-1.132-.915-2.742-2.307-5.006-2.307c-5.832 0-9.445 7.704-11.447 7.704a14.9 14.9 0 0 0 8.231 2.48c4.897 0 8.232-2.132 8.222-7.877");
}

.szuqhzb0j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.712 43.659s14.756-15.117 14.756-24.244a14.756 14.756 0 0 0-29.512 0c0 9.127 14.756 24.244 14.756 24.244");
}

.wq64e8kke {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.276 15.526c1.132.914 2.742 2.307 5.006 2.307c5.832 0 9.445-7.704 11.447-7.704a14.9 14.9 0 0 0-8.23-2.481c-4.898 0-8.232 2.133-8.223 7.878");
}

</style>

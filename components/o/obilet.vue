<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="g7xro2bmj"/><circle class="yaffovbtx"/><path class="k34seht7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:obilet" /></template>
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

.g7xro2bmj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.11 27.486c-1.16 0-2.11-.95-2.11-2.11v-1.372c0-1.161.95-2.11 2.11-2.11h0c1.161 0 2.111.949 2.111 2.11v1.372c0 1.16-.95 2.11-2.11 2.11");
}

.k34seht7c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.752 21.788v5.698m2.26-8.547v7.387c0 .633.422 1.055 1.055 1.055h.317m8.244-7.281v6.331c0 .633.422 1.055 1.055 1.055H37m-2.533-5.698h2.322m-4.069 4.538c-.317.633-1.056 1.055-1.794 1.055h0c-1.161 0-2.11-.95-2.11-2.11v-1.373c0-1.16.949-2.11 2.11-2.11h0c1.16 0 2.11.95 2.11 2.11v.739h-4.22m-11.476-.739c0-1.16.95-2.11 2.11-2.11h0c1.16 0 2.11.95 2.11 2.11v1.372c0 1.161-.95 2.11-2.11 2.11h0c-1.16 0-2.11-.949-2.11-2.11m-.001 2.216v-8.442");
}

.yaffovbtx {
  cx: 23.752px;
  cy: 19.255px;
  r: 0.75px;
  fill: currentColor;
}

</style>

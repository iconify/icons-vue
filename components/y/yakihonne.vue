<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cg73uzney"/><path class="zqk_lxkgg"/><path class="z_sjgx_hc"/><path class="wx9eex5xs"/><path class="f4_hgjiae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yakihonne" /></template>
<style>
.cg73uzney {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.895 12.591v6.694l-8.615 5.414L17.793 43.5l-5.122-27.009zL28.213 4.5");
}

.f4_hgjiae {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.751 24.699l4.424-3.988V17.01l-4.424 2.915zM28.213 4.5l4.002 5.501m0 3.696L28.213 4.5");
}

.wx9eex5xs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.447 18.808l3.325-2.935v-3.631l-3.325 3.285z");
}

.z_sjgx_hc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.496 22.653l.131 4.967l-4.624 4.675l-.355-5.088zM17.793 43.5l5.21-11.205m9.212-18.598l3.114-2.91V7.09l-3.114 2.911z");
}

.zqk_lxkgg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.7 22.55v8.55s-1.746 11.832-1.907 12.4l3.915-15.41l5.02-4.716L28.214 4.5l-3.318 14.785");
}

</style>

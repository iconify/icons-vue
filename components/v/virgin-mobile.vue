<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jbsdfi7_w"/><path class="nbyj28sgc"/><path class="ji28fbc2z"/><circle class="f29en5btg"/><circle class="t3u3eza2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:virgin-mobile" /></template>
<style>
.f29en5btg {
  cx: 19.914px;
  cy: 20.859px;
  r: 0.749px;
  fill: currentColor;
}

.jbsdfi7_w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.312 24.653l1.651-4.43L16 31.085c.74-7.57 2.481-14.131 5.407-19.49m-1.63 11.477l-.317 3.994m2.601-1.343l.099-3.672l1.447-.693m2.683-1.523c-.92.145-1.221 1.532-1.403 2.787c-.38 2.653 1.93 1.92 2.827.578m.089-3.64l-.28 14.01m2.637-15.212l-.253 3.435m2.295-.934l.124-2.732c.85-1.058 2.1-2.535 2.75-1.686c.854 1.116-.708 3.99 1.077 3.808");
}

.ji28fbc2z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 6.595c0 .018.008 23.374.005 34.81c8.678-1.52 27.86-4.845 36.995-6.427V10.595c-7.458-.824-35.596-3.925-37-4");
}

.nbyj28sgc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.826 19.769c-3.844.607-19.443 11.86-19.18 13.135");
}

.t3u3eza2c {
  cx: 30.274px;
  cy: 16.317px;
  r: 0.749px;
  fill: currentColor;
}

</style>

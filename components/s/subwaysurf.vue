<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nikvl5bke"/><path class="mnno_xzpl"/><circle class="oo-nu2f4c"/><path class="ltnm-cc9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:subwaysurf" /></template>
<style>
.ltnm-cc9e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.93 18.2h22.14M12.93 38.23h22.14m-15.34-4.66a3.85 3.85 0 0 0 3.36 1.5h2a3.43 3.43 0 0 0 3.42-3.43h0a3.42 3.42 0 0 0-3.42-3.42h-2.21a3.43 3.43 0 0 1-3.42-3.43h0a3.43 3.43 0 0 1 3.42-3.43h2a3.83 3.83 0 0 1 3.36 1.51");
}

.mnno_xzpl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.22 4.5h-8.44l-1.05 6.32h10.54z");
}

.nikvl5bke {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.15 10.82h13.7A4.22 4.22 0 0 1 35.07 15v26.39A2.11 2.11 0 0 1 33 43.5H15a2.11 2.11 0 0 1-2.11-2.11V15a4.22 4.22 0 0 1 4.26-4.18");
}

.oo-nu2f4c {
  cx: 24px;
  cy: 7.66px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

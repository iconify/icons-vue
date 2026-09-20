<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uahg2ub7t"/><circle class="nd7mojwup"/><path class="d93ctdbaa"/><circle class="chv8jzbro"/><circle class="kz393lbzm"/><path class="kd_-n-bey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:photo-pro" /></template>
<style>
.chv8jzbro {
  cx: 26.956px;
  cy: 25.927px;
  r: 6.572px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.d93ctdbaa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.663 37.876H6.775a2.26 2.26 0 0 1-2.26-2.26V13.971h18.148m8.586 0h12.266v21.645a2.26 2.26 0 0 1-2.26 2.26H31.249m11.466-23.905v-3.493h-8.284v3.493m-.001 0v-3.16L31.943 6.5H21.97l-2.489 4.31v3.161");
}

.kd_-n-bey {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.43 11.417H19.482");
}

.kz393lbzm {
  cx: 26.956px;
  cy: 25.927px;
  r: 10.173px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nd7mojwup {
  cx: 26.956px;
  cy: 25.924px;
  r: 12.7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.uahg2ub7t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.867 14.701v-3.196h-7.581V14.7");
}

</style>

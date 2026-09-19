<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hpbrwq39r"/><path class="l4x-f5bjl"/><path class="g_kf4iymp"/><circle class="gigdwtsmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mini-desktop" /></template>
<style>
.g_kf4iymp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.457 32.925c.68 4.18-1.769 7.573-6.556 7.83c2.465-3.21 1.005-6.337 1.005-6.337m-6.05-3.867l3.841 3.841m-2.375-11.601l10.135 10.134M16.819 19.99l11.44 11.441m3.312-22.479l7.735 7.735");
}

.gigdwtsmh {
  cx: 28.968px;
  cy: 19.29px;
  r: 3.892px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hpbrwq39r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.323 22.79c-4.18-.679-7.573 1.77-7.831 6.557c3.21-2.466 6.337-1.006 6.337-1.006");
}

.l4x-f5bjl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.237 40.01c5.705-.2 8.858-2.78 9.46-5.618c0 0 7.281 1.319 15.738-7.138c7.51-7.51 7.051-19.493 7.051-19.493s-11.982-.458-19.493 7.052c-8.456 8.457-7.137 15.738-7.137 15.738c-2.838.602-5.418 3.755-5.619 9.46");
}

</style>

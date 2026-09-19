<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="boat33k0c"/><circle class="x5-6ds4jl"/><circle class="b0mycdqkm"/><circle class="u_7rv5b_y"/><circle class="f10akswjj"/><path class="hw_ffjfww"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mapas-de-espaa" /></template>
<style>
.b0mycdqkm {
  cx: 19.431px;
  cy: 26.458px;
  r: 2.054px;
}

.boat33k0c {
  d: path("M7.023 6.907v8.216m8.587-5.495a2.72 2.72 0 0 0-2.72-2.721h0a2.72 2.72 0 0 0-2.722 2.721v2.773a2.72 2.72 0 0 0 2.721 2.722h0a2.72 2.72 0 0 0 2.722-2.722h-2.722m5.73 2.722V6.907l5.443 8.216V6.907");
}

.f10akswjj {
  cx: 37.621px;
  cy: 8.333px;
  r: 2.054px;
}

.hw_ffjfww {
  d: path("m9.608 25.068l7.62 1.478m4.336-.581l7.672-5.069m3.361-3.083l3.855-7.546m-.002 13.428a6.05 6.05 0 0 0-6.051 6.05c0 4.739 4.622 10.452 5.828 11.848a.37.37 0 0 0 .56 0c1.178-1.387 5.713-7.11 5.713-11.847a6.05 6.05 0 0 0-6.05-6.051m0 8.32a2.265 2.265 0 1 1 2.26-2.27v.005a2.26 2.26 0 0 1-2.26 2.26z");
}

.u_7rv5b_y {
  cx: 31.011px;
  cy: 19.461px;
  r: 2.054px;
}

.x5-6ds4jl {
  cx: 7.554px;
  cy: 24.611px;
  r: 2.054px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

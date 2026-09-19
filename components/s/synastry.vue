<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="rx8_-9z8b"/><path class="iu04o2bwc"/><path class="z7zq_9bvk"/><circle class="v509zkd1j"/><circle class="gc0nm9bla"/><circle class="dz_rrzsmr"/><circle class="h9mbabc3x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:synastry" /></template>
<style>
.dz_rrzsmr {
  cx: 21.765px;
  cy: 19.488px;
  r: 1.874px;
}

.gc0nm9bla {
  cx: 35.026px;
  cy: 26.227px;
  r: 1.874px;
}

.h9mbabc3x {
  cx: 36.002px;
  cy: 10.531px;
  r: 1.127px;
}

.iu04o2bwc {
  d: path("M23.38 9.3c-3.929-.027-7.253 1.611-8.845 4.359c-2.613 4.508.131 10.611 6.129 13.631h0c4.355 2.192 9.42 2.217 12.87.064a1.87 1.87 0 0 1-.382-1.126c0-1.035.838-1.875 1.873-1.876q0 0 0 0c.412.002.813.139 1.14.39l.092-.148c2.613-4.509-.132-10.612-6.13-13.631h-.001C28.005 9.893 25.66 9.316 23.38 9.3");
}

.rx8_-9z8b {
  d: path("M35.21 9.685a25 25 0 0 0-3.424-2.172c-3.427-1.808-7.21-2.803-10.898-2.864c-6.55-.11-12.11 2.722-14.76 7.516c-4.301 7.78.216 18.31 10.087 23.52a25.3 25.3 0 0 0 4.814 1.93a4.65 4.65 0 0 1 4.507-3.561a4.65 4.65 0 0 1 4.633 4.317c5.24-.681 9.495-3.349 11.704-7.339c3.446-6.235 1.229-14.237-4.87-19.85");
}

.v509zkd1j {
  cx: 25.535px;
  cy: 38.704px;
  r: 4.65px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z7zq_9bvk {
  d: path("M24.71 13.352c-1.725.094-3.153.861-3.864 2.076c-.46.796-.585 1.735-.356 2.691a1.87 1.87 0 0 1 1.275-.505a1.874 1.874 0 0 1 1.875 1.873v.002a1.87 1.87 0 0 1-1.065 1.687c.377.296.79.557 1.23.777c2.896 1.446 6.267.868 7.528-1.29v-.001c1.263-2.159-.062-5.08-2.958-6.526c-1.155-.575-2.443-.851-3.665-.784");
}

</style>

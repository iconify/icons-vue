<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="wv5f_1brg"/><path class="gnv_jpkgl"/><circle class="cwxjr7bpn"/><path class="q6kmdca-i"/><circle class="j1-unv-pk"/><circle class="r1rdusoit"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:onboarding-sharp" /></template>
<style>
.cwxjr7bpn {
  cx: 5px;
  cy: 19.5px;
  r: 1.75px;
}

.gnv_jpkgl {
  d: path("M7.5 15.25h9.75v-.75c0-2.6-2.3-4.25-5.25-4.25S6.75 11.9 6.75 14.5v.75z");
}

.j1-unv-pk {
  cx: 12px;
  cy: 19.5px;
  r: 1.75px;
}

.q6kmdca-i {
  d: path("M7.75 19.5h1.5m5.5 0h1.5");
}

.r1rdusoit {
  cx: 19px;
  cy: 19.5px;
  r: 1.75px;
}

.wv5f_1brg {
  cx: 12px;
  cy: 5.25px;
  r: 2.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

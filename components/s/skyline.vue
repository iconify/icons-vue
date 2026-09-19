<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="t16p5-boz"/><g class="y9tr6bcfx"><circle class="bqdseed6k"/><circle class="n_25b_b_s"/><circle class="bj95ygb6l"/><path class="ifvq4batr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:skyline" /></template>
<style>
.bj95ygb6l {
  cx: 12.412px;
  cy: 23.959px;
  r: 6.905px;
}

.bqdseed6k {
  cx: 24.156px;
  cy: 35.595px;
  r: 6.905px;
}

.ifvq4batr {
  d: path("M21.094 6.272c-1.54 3.965-1.497 7.945-.069 12.255m5.415.179c-2.505-.938-4.139-3.582-4.005-6.479s2.005-5.345 4.583-6m2.714 14.645c1.833.614 6.225 5.991 6.913 9.564M18.55 26.912c-1.833-.613-6.225-5.99-6.913-9.564m10.22 24.668c2.659-.79 4.471-3.482 4.374-6.499c-.096-3.017-2.076-5.564-4.778-6.148m5.904.25c1.54 3.966 1.497 7.738.069 12.049");
}

.n_25b_b_s {
  cx: 35.588px;
  cy: 23.959px;
  r: 6.905px;
}

.t16p5-boz {
  cx: 24.156px;
  cy: 12.405px;
  r: 6.905px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

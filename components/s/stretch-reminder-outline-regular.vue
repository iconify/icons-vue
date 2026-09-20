<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rm1tb6aya"/><path class="z1h8pnb6e"/><path class="r_4k1sbsg"/><path class="ph1z-dbce"/><path class="bbxz-u7vo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stretch-reminder-outline-regular" /></template>
<style>
.bbxz-u7vo {
  d: path("M16 6a6 6 0 0 1 0 12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ph1z-dbce {
  d: path("M16 9a3 3 0 0 1 0 6");
}

.r_4k1sbsg {
  d: path("M7 13h6");
}

.rm1tb6aya {
  d: path("M4 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.z1h8pnb6e {
  d: path("M7 8v5l4 4v4");
}

</style>

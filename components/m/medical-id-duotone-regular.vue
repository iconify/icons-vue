<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t6f8lsb5t"/><path class="w2535ybvu"/><path class="qrhxojbpd"/><path class="hv3ppsbji"/><path class="acx2mjbnt"/><path class="ikiprn9sq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:medical-id-duotone-regular" /></template>
<style>
.acx2mjbnt {
  d: path("M12 11v6");
}

.hv3ppsbji {
  d: path("M11 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.ikiprn9sq {
  d: path("M9 14h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qrhxojbpd {
  d: path("M7 6a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
}

.t6f8lsb5t {
  fill: currentColor;
  d: path("M7 6a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.w2535ybvu {
  fill: currentColor;
  d: path("M11 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

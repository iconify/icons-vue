<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><path id="SVGhFODPdva" class="nz_949bej"/></defs><use href="#SVGhFODPdva" class="c-zrgpb5l"/><use href="#SVGhFODPdva" class="c-zrgpb5l"/><path class="zxxn9x_5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:proton-drive" /></template>
<style>
.c-zrgpb5l {
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nz_949bej {
  fill: none;
  stroke: currentColor;
  d: path("M4.5 36.103V11.897a4.035 4.035 0 0 1 4.034-4.035h7.567a3.6 3.6 0 0 1 2.122.695l2.532 1.86a3.6 3.6 0 0 0 2.123.695h16.588a4.035 4.035 0 0 1 4.034 4.035v20.956a4.035 4.035 0 0 1-4.035 4.035H8.535A4.035 4.035 0 0 1 4.5 36.103");
}

.zxxn9x_5i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.207 40.138v-21.05a3.14 3.14 0 0 0-3.156-3.139l-15.276.088a3.14 3.14 0 0 1-1.837-.58l-3.402-2.419a3.14 3.14 0 0 0-1.818-.58H4.5");
}

</style>

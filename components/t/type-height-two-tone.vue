<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rk3kg3bjg"/><path class="y9g_tbcvw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:type-height-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rk3kg3bjg {
  stroke-opacity: 0.4;
  d: path("M2 7V6C2 4.8954 2.8954 4 4 4H10C11.1046 4 12 4.8954 12 6V7M7 4V20M3.5 20H10.5");
}

.y9g_tbcvw {
  d: path("M19 20V4M16 7L19 4L22 7M16 17L19 20L22 17");
}

</style>

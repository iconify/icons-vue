<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="z9q0lfi_k"/><path class="t_3j7e08c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shapes-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t_3j7e08c {
  d: path("M2.7071 2.7071L10.2929 10.2929M10.2929 2.7071L2.7071 10.2929");
}

.z9q0lfi_k {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 17.5C11 19.8472 8.8472 22 6.5 22C4.1528 22 2 19.8472 2 17.5C2 15.1528 4.1528 13 6.5 13C8.8472 13 11 15.1528 11 17.5ZM14 13L21 13C21.5523 13 22 13.4477 22 14L22 21C22 21.5523 21.5523 22 21 22L14 22C13.4477 22 13 21.5523 13 21L13 14C13 13.4477 13.4477 13 14 13ZM18.3944 2.5528L21.8944 9.5528C22.2269 10.2177 21.7434 11 21 11L14 11C13.2566 11 12.7731 10.2177 13.1056 9.5528L16.6056 2.5528C16.9741 1.8157 18.0259 1.8157 18.3944 2.5528Z");
  stroke: none;
}

</style>

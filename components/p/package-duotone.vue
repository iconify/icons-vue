<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vdklsob8k"/><path class="o6zniyb9r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:package-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o6zniyb9r {
  d: path("M2.3084 7.0066L12 12M12 12L21.6916 7.0066M12 12L12 22M7 4.3017L17 9.4239");
}

.vdklsob8k {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13.3613 1.3266L21.3613 5.4003C22.3668 5.9123 23 6.9453 23 8.0737L23 15.9263C23 17.0547 22.3668 18.0877 21.3613 18.5997L13.3613 22.6734C12.506 23.1089 11.494 23.1089 10.6387 22.6734L2.6387 18.5997C1.6332 18.0877 1 17.0547 1 15.9263L1 8.0737C1 6.9453 1.6332 5.9123 2.6387 5.4003L10.6387 1.3266C11.494 0.8911 12.506 0.8911 13.3613 1.3266Z");
  stroke: none;
}

</style>

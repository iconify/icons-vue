<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="rq_h4obhn"/><path class="blr6m8r6y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pilcrow-right-sharp-duotone" /></template>
<style>
.blr6m8r6y {
  d: path("M2 17L21 17M16.7071 12.7071L21 17L16.7071 21.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rq_h4obhn {
  stroke-opacity: 0.4;
  d: path("M15 3L6 3C4.3431 3 3 4.3431 3 6C3 7.6569 4.3431 9 6 9L8 9M8 3L8 14M13 3L13 14");
}

</style>

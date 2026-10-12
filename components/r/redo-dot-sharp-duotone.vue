<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="d07yu6btg"/><path class="i23jo_tjq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:redo-dot-sharp-duotone" /></template>
<style>
.d07yu6btg {
  stroke-opacity: 0.4;
  d: path("M2 19L2 18C2 11.6487 7.1487 6.5 13.5 6.5C16.55 6.5 19.4751 7.7116 21.6317 9.8683L22 10.2365M22 5L22 10.2365L16.7635 10.2365");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.i23jo_tjq {
  fill: currentColor;
  d: path("M11.5 17C11.5 18.1046 12.3954 19 13.5 19C14.6046 19 15.5 18.1046 15.5 17C15.5 15.8954 14.6046 15 13.5 15C12.3954 15 11.5 15.8954 11.5 17Z");
  stroke: none;
}

</style>

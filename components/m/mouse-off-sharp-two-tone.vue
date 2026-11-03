<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="kugsbb9pv"/><path class="znv6-wxbt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mouse-off-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kugsbb9pv {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M18.2181 18.2181C17.0152 20.5419 14.6167 22.0007 12 22C8.134 22 5 18.866 5 15L5 9C4.9983 7.8801 5.2665 6.7762 5.7819 5.7819L18.2181 18.2181ZM7.4354 3.6928C8.7054 2.5997 10.3255 1.9986 12.0011 1.9986C15.8675 1.9986 19.0014 5.1336 19 9L19 15C19 15.0843 18.9985 15.1686 18.9955 15.2529L7.4354 3.6928Z");
  stroke: none;
}

.znv6-wxbt {
  d: path("M17.4697 17.4697C16.5283 19.5515 14.4333 21 12 21C8.6863 21 6 18.3137 6 15L6 9C6 8.1196 6.1896 7.2835 6.5303 6.5303M1.7071 1.7071L22.2929 22.2929");
}

</style>

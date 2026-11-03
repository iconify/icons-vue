<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="osbh0jfbu"/><path class="ahhqo1b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mouse-off-sharp-fill" /></template>
<style>
.ahhqo1b4s {
  d: path("M1.7071 1.7071L22.2929 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.osbh0jfbu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.2181 18.2181C17.0152 20.5419 14.6167 22.0007 12 22C8.134 22 5 18.866 5 15L5 9C4.9983 7.8801 5.2665 6.7762 5.7819 5.7819L18.2181 18.2181ZM7.3895 3.7327C8.6657 2.6148 10.3045 1.9985 12.0011 1.9985C15.8675 1.9985 19.0014 5.1336 19 9L19 15C19 15.1118 18.9974 15.2236 18.9921 15.3353L7.3895 3.7327Z");
  stroke: none;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="srz1q5wvy"/><path class="k8br464fy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-rows-move-up-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.k8br464fy {
  d: path("M6 4L3 4L3 22L21 22L21 4L18 4M3 13L21 13M12 9L12 2M8.7071 5.2929L12 2L15.2929 5.2929");
}

.srz1q5wvy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 13L3 22L21 22L21 13Z");
  stroke: none;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dl_h0hnvp"/><path class="p-ona3bvk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:teapot-duotone" /></template>
<style>
.dl_h0hnvp {
  stroke-opacity: 0.4;
  d: path("M18 16.5C20 16.5 18.5 11.5 22 11M6.2764 12.5H4C2.8954 12.5 2 13.3954 2 14.5C2 15.6046 2.8954 16.5 4 16.5H6M9 9.5V7C9 5.89543 9.89543 5 11 5H12M15 9.5V7C15 5.89543 14.1046 5 13 5H12M12 5V4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p-ona3bvk {
  fill: currentColor;
  d: path("M7.1172 9.6963C8.3918 8.634 10.1214 8 12 8C13.8786 8 15.6082 8.634 16.8828 9.6963C18.1596 10.7602 19 12.2775 19 14L19 18C19 19.6569 17.6569 21 16 21L8 21C6.3431 21 5 19.6569 5 18L5 14C5 12.2775 5.8404 10.7602 7.1172 9.6963Z");
  stroke: none;
}

</style>

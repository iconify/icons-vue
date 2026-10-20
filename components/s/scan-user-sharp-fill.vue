<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="r81iret_p"/><path clip-rule="evenodd" class="cnov7lb3p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scan-user-sharp-fill" /></template>
<style>
.cnov7lb3p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.5 7.5C14.5 8.8807 13.3807 10 12 10C10.6193 10 9.5 8.8807 9.5 7.5C9.5 6.1193 10.6193 5 12 5C13.3807 5 14.5 6.1193 14.5 7.5ZM8 12L16 12C16.5523 12 17 12.4477 17 13L17 17C17 17.5523 16.5523 18 16 18L8 18C7.4477 18 7 17.5523 7 17L7 13C7 12.4477 7.4477 12 8 12Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r81iret_p {
  d: path("M3 9L3 3L9 3M15 3L21 3L21 9M21 15L21 21L15 21M9 21L3 21L3 15");
}

</style>

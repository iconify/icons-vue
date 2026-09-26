<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="vippwpb-d"/><path class="olki8_c8y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mic-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.olki8_c8y {
  d: path("M19 10L19 11C19 14.866 15.866 18 12 18C8.134 18 5 14.866 5 11L5 10M12 18L12 22M7 22L17 22");
}

.vippwpb-d {
  fill: currentColor;
  d: path("M12 1C14.2091 1 16 2.7909 16 5L16 11C16 13.2091 14.2091 15 12 15C9.7909 15 8 13.2091 8 11L8 5C8 2.7909 9.7909 1 12 1Z");
  stroke: none;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="gz-8zybbv"/><path class="jkg_acc2e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mic-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.gz-8zybbv {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 1C14.2091 1 16 2.7909 16 5L16 11C16 13.2091 14.2091 15 12 15C9.7909 15 8 13.2091 8 11L8 5C8 2.7909 9.7909 1 12 1Z");
  stroke: none;
}

.jkg_acc2e {
  d: path("M9 5C9 3.3431 10.3431 2 12 2C13.6569 2 15 3.3431 15 5L15 11C15 12.6569 13.6569 14 12 14C10.3431 14 9 12.6569 9 11L9 5ZM19 10L19 11C19 14.866 15.866 18 12 18C8.134 18 5 14.866 5 11L5 10M12 18L12 22M7 22L17 22");
}

</style>

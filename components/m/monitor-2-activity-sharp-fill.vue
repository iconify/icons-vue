<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="etc3uq8zn"/><path class="m77kogrek"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:monitor-2-activity-sharp-fill" /></template>
<style>
.etc3uq8zn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2 2L22 2C22.5523 2 23 2.4477 23 3L23 17C23 17.5523 22.5523 18 22 18L2 18C1.4477 18 1 17.5523 1 17L1 3C1 2.4477 1.4477 2 2 2ZM6 9L6 11L8.5 11C8.8788 11 9.225 10.786 9.3944 10.4472L10.1238 8.9885L13.1679 13.5547C13.3657 13.8513 13.7064 14.0202 14.0621 13.9981C14.4179 13.9759 14.735 13.7661 14.8944 13.4472L16.118 11L18 11L18 9L15.5 9C15.1212 9 14.775 9.214 14.6056 9.5528L13.8762 11.0115L10.8321 6.4453C10.6343 6.1487 10.2936 5.9798 9.9379 6.0019C9.5821 6.0241 9.265 6.2339 9.1056 6.5528L7.882 9Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.m77kogrek {
  d: path("M12 17L12 21M7 21L17 21");
}

</style>

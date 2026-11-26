<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="u31xc-wiq"/><path class="hm0cwqhau"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:whistle-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hm0cwqhau {
  d: path("M15 5L15 7L15 8M9 9.5C10.3807 9.5 11.5 10.6193 11.5 12C11.5 13.3807 10.3807 14.5 9 14.5C7.6193 14.5 6.5 13.3807 6.5 12C6.5 10.6193 7.6193 9.5 9 9.5ZM15 5L22 5L22 9L15.9826 11.5072C15.9942 11.6712 16 11.8356 16 12C16 15.866 12.866 19 9 19C5.134 19 2 15.866 2 12C2 8.134 5.134 5 9 5Z");
}

.u31xc-wiq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3.3431 6.3431C1.8965 7.7898 1 9.7911 1 12C1 16.4183 4.5817 20 9 20C13.3624 20 16.9092 16.5084 16.9983 12.1673L22.3846 9.9231C22.7573 9.7678 23 9.4037 23 9L23 5C23 4.4477 22.5523 4 22 4L15 4L9 4C6.7911 4 4.7898 4.8965 3.3431 6.3431Z");
  stroke: none;
}

</style>

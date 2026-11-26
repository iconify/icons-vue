<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="j3leilbxt"/><path class="m77kogrek"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:monitor-2-user-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.j3leilbxt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2 2L22 2C22.5523 2 23 2.4477 23 3L23 17C23 17.5523 22.5523 18 22 18L2 18C1.4477 18 1 17.5523 1 17L1 3C1 2.4477 1.4477 2 2 2ZM14.1213 11.1213C14.6631 10.5795 15 9.8282 15 9C15 7.3431 13.6569 6 12 6C10.3431 6 9 7.3431 9 9C9 10.6569 10.3431 12 12 12C12.8282 12 13.5795 11.6631 14.1213 11.1213ZM7.1707 16L16.8293 16C16.4175 14.8348 15.3063 14 14 14L10 14C8.6937 14 7.5825 14.8348 7.1707 16Z");
  stroke: none;
}

.m77kogrek {
  d: path("M12 17L12 21M7 21L17 21");
}

</style>

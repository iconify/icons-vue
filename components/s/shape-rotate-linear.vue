<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="k_5zf_j_h"/><path class="l52h71b_b"/><path class="rc-03b_nz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shape-rotate-linear" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k_5zf_j_h {
  d: path("M18.4439 19.122L19.1222 18.444C21.0407 16.525 22 15.566 22 14.374C22 13.182 21.0407 12.223 19.1222 10.304L13.6958 4.878C11.7772 2.959 10.818 2 9.6259 2C8.4339 2 7.4746 2.959 5.5561 4.878L4.8778 5.556C2.9593 7.475 2 8.434 2 9.626C2 10.818 2.9593 11.777 4.8778 13.696L10.3042 19.122C12.2228 21.041 13.182 22 14.3741 22C15.5661 22 16.5254 21.041 18.4439 19.122Z");
}

.l52h71b_b {
  stroke-linejoin: round;
  d: path("M20.5 6.986L22 8C22 4.985 19.8377 2.483 17 2");
}

.rc-03b_nz {
  stroke-linejoin: round;
  d: path("M3.5 17.014L2 16C2 19.015 4.1623 21.517 7 22");
}

</style>

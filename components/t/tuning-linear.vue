<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="y0arut6ax"/><path class="e66wveb3k"/><path class="bvwq-0kiq"/><path class="itr5k-b-e"/><path class="htq9jdyaq"/><path class="ny4-c4djh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tuning-linear" /></template>
<style>
.bvwq-0kiq {
  d: path("M16.959 9L16.959 2");
}

.e66wveb3k {
  d: path("M3.99998 9.5C3.99998 11.1569 5.34312 12.5 6.99998 12.5C8.65683 12.5 9.99998 11.1569 9.99998 9.5C9.99998 7.84315 8.65683 6.5 6.99998 6.5C5.34312 6.5 3.99998 7.84315 3.99998 9.5Z");
}

.htq9jdyaq {
  d: path("M16.959 22L16.959 20");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.itr5k-b-e {
  d: path("M6.95898 15L6.95898 22");
}

.ny4-c4djh {
  d: path("M6.95898 2L6.95898 4");
}

.y0arut6ax {
  d: path("M14 14.5C14 12.8431 15.3431 11.5 17 11.5C18.6568 11.5 20 12.8431 20 14.5C20 16.1569 18.6568 17.5 17 17.5C15.3431 17.5 14 16.1569 14 14.5Z");
}

</style>

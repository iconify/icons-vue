<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="fa7lsebpo"/><path class="qsgur_bab"/><path class="ko6o-6b9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-sort-vertical-broken" /></template>
<style>
.fa7lsebpo {
  stroke-linejoin: round;
  d: path("M9.5 8L9.5 16M12 13.25L9.5 16L7 13.25");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ko6o-6b9b {
  d: path("M7 3.33782C8.47087 2.48697 10.1786 2 12 2C17.5228 2 22 6.47715 22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 10.1786 2.48697 8.47087 3.33782 7");
}

.qsgur_bab {
  stroke-linejoin: round;
  d: path("M14.5 16L14.5 8M17 10.75L14.5 8L12 10.75");
}

</style>

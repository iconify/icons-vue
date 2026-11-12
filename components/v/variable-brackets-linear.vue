<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bhs8rm6xm"/><path class="rv8m0xbux"/><path class="rulrh0btp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:variable-brackets-linear" /></template>
<style>
.bhs8rm6xm {
  d: path("M17 7.99991C14 8.99991 12 11.9999 12 11.9999M12 11.9999C12 11.9999 10 14.9999 7 15.9999M12 11.9999C12 11.9999 11 6.99991 9 7.99991M12 11.9999C12 11.9999 13 16.9999 15 15.9999");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rulrh0btp {
  d: path("M16 22C19 20.268 22 16.6925 22 12C22 7.30754 19 3.73205 16 2");
}

.rv8m0xbux {
  d: path("M8 22C5 20.268 2 16.6925 2 12C2 7.30754 5 3.73205 8 2");
}

</style>

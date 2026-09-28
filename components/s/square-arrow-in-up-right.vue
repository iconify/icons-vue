<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8_1_zqwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-arrow-in-up-right" /></template>
<style>
.a8_1_zqwu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 17L18 17C19.6569 17 21 15.6569 21 14L21 6C21 4.3431 19.6569 3 18 3L10 3C8.3431 3 7 4.3431 7 6L7 9M3 21L10.5 13.5M3 13L10.5 13C10.7761 13 11 13.2239 11 13.5L11 21");
}

</style>

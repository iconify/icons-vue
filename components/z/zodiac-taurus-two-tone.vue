<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2eu97loi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:zodiac-taurus-two-tone" /></template>
<style>
.z2eu97loi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 11C14.7614 11 17 13.2386 17 16C17 18.7614 14.7614 21 12 21C9.2386 21 7 18.7614 7 16C7 13.2386 9.2386 11 12 11ZM4 3C4 7.4183 7.5817 11 12 11C16.4183 11 20 7.4183 20 3");
}

</style>

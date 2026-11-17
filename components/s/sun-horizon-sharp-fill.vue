<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtcjb_xkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sun-horizon-sharp-fill" /></template>
<style>
.rtcjb_xkp {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 16V15C7.5 12.515 9.515 10.5 12 10.5C14.485 10.5 16.5 12.515 16.5 15V16M1 15H4.5M19.5 15H23M4.636 7.636L6.282 9.283M19.364 7.636L17.718 9.283M12 7.5V4M3 19H21");
}

</style>

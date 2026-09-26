<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mcfz5vz2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:quote-end-sharp" /></template>
<style>
.mcfz5vz2x {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 9.5C10 12.9659 8.2018 16.1837 5.25 18C5.9991 17.3614 6.4306 16.4265 6.4306 15.4421C6.4306 14.2412 5.79 13.1315 4.75 12.5311C3.6671 11.9059 3 10.7504 3 9.5C3 7.567 4.567 6 6.5 6C8.433 6 10 7.567 10 9.5ZM21 9.5C21 12.9659 19.2018 16.1837 16.25 18C16.9991 17.3614 17.4306 16.4265 17.4306 15.4421C17.4306 14.2412 16.79 13.1315 15.75 12.5311C14.6671 11.9059 14 10.7504 14 9.5C14 7.567 15.567 6 17.5 6C19.433 6 21 7.567 21 9.5Z");
}

</style>

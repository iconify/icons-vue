<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rne0stlnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:teacher-sharp" /></template>
<style>
.rne0stlnu {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 12C9.5 13.3807 8.3807 14.5 7 14.5C5.6193 14.5 4.5 13.3807 4.5 12C4.5 10.6193 5.6193 9.5 7 9.5C8.3807 9.5 9.5 10.6193 9.5 12ZM5 18.5L9 18.5C10.6569 18.5 12 19.8431 12 21.5L12 22L2 22L2 21.5C2 19.8431 3.3431 18.5 5 18.5ZM9 6.5917L9 2L22 2L22 15L12.1235 15M12 6.5L19 6.5M13 10.5L19 10.5");
}

</style>

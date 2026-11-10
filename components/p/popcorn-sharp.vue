<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qnxvxibms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:popcorn-sharp" /></template>
<style>
.qnxvxibms {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 11C4.371 10.53 4 9.79 4 9C4 7.62 5.119 6.5 6.5 6.5C6.863 6.5 7.221 6.58 7.55 6.73C7.192 6.22 7 5.62 7 5C7 3.34 8.343 2 10 2C11.482 2 12.742 3.08 12.966 4.55C13.435 3.89 14.193 3.5 15 3.5C16.381 3.5 17.5 4.62 17.5 6C17.5 6.17 17.483 6.34 17.449 6.5C17.466 6.5 17.483 6.5 17.5 6.5C18.881 6.5 20 7.62 20 9C20 9.79 19.629 10.53 19 11M9 11L10 22M15 11L14 22M4 11H20L18 22H6L4 11Z");
}

</style>

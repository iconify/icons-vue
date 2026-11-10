<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7yshkj6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:rotate-3d" /></template>
<style>
.g7yshkj6f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 12C2 17.52 6.4771 22 12 22C17.5229 22 22 17.52 22 12M2 12C2 6.48 6.4771 2 12 2C17.5229 2 22 6.48 22 12M2 12L4.3223 13.03C6.0968 13.82 7.9823 14.33 9.9123 14.55C11.2999 14.7 12.7001 14.7 14.0877 14.55C16.0177 14.33 17.9032 13.82 19.6778 13.03L22 12M10.8889 21.44L9.8449 19.62C9.0645 18.25 8.5094 16.77 8.2009 15.23C7.776 13.1 7.8306 10.9 8.3562 8.8C8.5621 7.97 8.8401 7.17 9.185 6.39L10.8889 2.56");
}

</style>

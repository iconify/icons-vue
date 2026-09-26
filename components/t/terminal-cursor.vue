<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yq8o9f3-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:terminal-cursor" /></template>
<style>
.yq8o9f3-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 18.9999H13M14.7026 5.35175L11.5789 14.9795C11.4412 15.4136 10.8422 15.4525 10.6494 15.04L8.61378 10.6858C8.56101 10.573 8.46799 10.4838 8.35296 10.436L4.30741 8.72095C3.88071 8.54335 3.90275 7.93152 4.34114 7.78509L14.0677 4.72626C14.4554 4.59674 14.8263 4.96206 14.7026 5.35175Z");
}

</style>

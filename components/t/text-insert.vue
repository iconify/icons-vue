<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dj-95e6at"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:text-insert" /></template>
<style>
.dj-95e6at {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 3H21M15 9H21M3 15H21M3 21H21M8.6 3L11 5.25L8.6 7.5M11 5.25H4.6C3.7164 5.25 3 5.92 3 6.75V9");
}

</style>

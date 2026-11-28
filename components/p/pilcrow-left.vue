<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_9fw8bbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pilcrow-left" /></template>
<style>
.h_9fw8bbn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 3H13C11.3431 3 10 4.3431 10 6C10 7.6569 11.3431 9 13 9H15M15 3V13M20 3V13M21 17H3M7 13L3 17L7 21");
}

</style>

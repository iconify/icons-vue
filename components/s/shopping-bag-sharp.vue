<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqzu86jcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shopping-bag-sharp" /></template>
<style>
.bqzu86jcm {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.0572 7L19.9428 7M15 10L15 11C15 12.6569 13.6569 14 12 14C10.3431 14 9 12.6569 9 11L9 10M7 3L16.9999 3L20 7L20 21L4 21L4 7L7 3Z");
}

</style>

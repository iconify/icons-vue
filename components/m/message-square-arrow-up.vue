<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="malec7bkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-arrow-up" /></template>
<style>
.malec7bkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 3L18 3C19.6569 3 21 4.3431 21 6L21 14C21 15.6569 19.6569 17 18 17L7 17L3 21L3 6C3 4.3431 4.3431 3 6 3ZM12 13V7M9 10L12 7L15 10");
}

</style>

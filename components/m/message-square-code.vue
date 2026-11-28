<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdblifbro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-code" /></template>
<style>
.fdblifbro {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 3L18 3C19.6569 3 21 4.3431 21 6L21 14C21 15.6569 19.6569 17 18 17L7 17L3 21L3 6C3 4.3431 4.3431 3 6 3ZM10 7.5L7.5 10L10 12.5M14 7.5L16.5 10L14 12.5");
}

</style>

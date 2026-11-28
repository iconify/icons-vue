<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kimbgrcdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:squares-divide" /></template>
<style>
.kimbgrcdt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 3L13 3C14.1046 3 15 3.8954 15 5L15 13C15 14.1046 14.1046 15 13 15L5 15C3.8954 15 3 14.1046 3 13L3 5C3 3.8954 3.8954 3 5 3ZM11 9L19 9C20.1046 9 21 9.8954 21 11L21 19C21 20.1046 20.1046 21 19 21L11 21C9.8954 21 9 20.1046 9 19L9 11C9 9.8954 9.8954 9 11 9Z");
}

</style>

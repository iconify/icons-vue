<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmpa3bbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:security-key-sharp" /></template>
<style>
.pmpa3bbtd {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 2L18 2L18 16L6 16ZM9 16L9 22L15 22L15 16M14 9C14 10.1046 13.1046 11 12 11C10.8954 11 10 10.1046 10 9C10 7.8954 10.8954 7 12 7C13.1046 7 14 7.8954 14 9Z");
}

</style>

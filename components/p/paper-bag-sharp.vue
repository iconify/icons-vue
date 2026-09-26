<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="af9nscbar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:paper-bag-sharp" /></template>
<style>
.af9nscbar {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 21L3 3L4 3C4.5409 3 5.0673 3.1754 5.5 3.5C5.9327 3.8246 6.4591 4 7 4C7.5409 4 8.0673 3.8246 8.5 3.5C8.9327 3.1754 9.4591 3 10 3C10.5409 3 11.0673 3.1754 11.5 3.5C11.9327 3.8246 12.4591 4 13 4C13.5409 4 14.0673 3.8246 14.5 3.5C14.9327 3.1754 15.4591 3 16 3L17 3L21 21L3 21ZM17 3L17 21M7 8L13 8");
}

</style>

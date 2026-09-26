<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jof85mv9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:megaphone-sharp" /></template>
<style>
.jof85mv9e {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M22 4.071L22 17.429C22 17.628 21.935 17.823 21.813 17.992C21.691 18.161 21.517 18.298 21.309 18.387C21.101 18.476 20.869 18.516 20.638 18.496C20.407 18.478 20.186 18.405 20 18.286C18.788 17.48 17.42 16.614 16 16L13.6873 15L2 15L2 6.5L13.6873 6.5L16 5.5C17.42 4.886 18.788 4.02 20 3.214C20.186 3.095 20.407 3.022 20.638 3.004C20.869 2.986 21.101 3.024 21.309 3.113C21.517 3.202 21.691 3.339 21.813 3.508C21.935 3.677 22 3.872 22 4.071ZM10 15L10 21L8 21C6.2 21 5.5 18.5 5.5 15M16 5.5L16 16");
}

</style>

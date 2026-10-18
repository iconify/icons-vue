<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7dyxuk0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:play-pause" /></template>
<style>
.z7dyxuk0j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 7.5C2 6.6716 2.6716 6 3.5 6C3.8011 6 4.0951 6.0906 4.344 6.26L11.5626 11.1733C11.8362 11.3595 12 11.6691 12 12C12 12.3309 11.8362 12.6405 11.5626 12.8267L4.344 17.74C4.0951 17.9094 3.8011 18 3.5 18C2.6716 18 2 17.3284 2 16.5L2 7.5ZM17 6L17 18M22 6L22 18");
}

</style>

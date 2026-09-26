<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jm9annv6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sticky-note-x-sharp" /></template>
<style>
.jm9annv6x {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 3L3 3L3 21L12 21M15 3L21 9L21 12M15 3L15 9L21 9M14.7071 14.7071L21.2929 21.2929M21.2929 14.7071L14.7071 21.2929");
}

</style>

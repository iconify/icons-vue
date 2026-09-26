<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtt3ujtqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sticky-note-off" /></template>
<style>
.xtt3ujtqd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3.8787 3.8787C3.3161 4.4413 3 5.2044 3 6L3 18C3 19.6569 4.3431 21 6 21L18 21C18.7956 21 19.5587 20.6839 20.1213 20.1213M8.6569 3L15 3L21 9L21 15.3431M15 3L15 6C15 7.6569 16.3431 9 18 9L21 9M2 2L22 22");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rw_ydpbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:parking" /></template>
<style>
.rw_ydpbiq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 13V9C9.5 8.45 9.9477 8 10.5 8H12C13.3807 8 14.5 9.12 14.5 10.5C14.5 11.88 13.3807 13 12 13H9.5ZM9.5 13V16M12 22C6.4772 22 2 17.52 2 12C2 6.48 6.4772 2 12 2C17.5228 2 22 6.48 22 12C22 17.52 17.5228 22 12 22Z");
}

</style>

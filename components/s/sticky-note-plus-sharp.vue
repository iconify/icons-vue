<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l84h-5chk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sticky-note-plus-sharp" /></template>
<style>
.l84h-5chk {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 3L3 3L3 21L12 21M15 3L21 9L21 12M15 3L15 9L21 9M18 14L18 22M14 18L22 18");
}

</style>

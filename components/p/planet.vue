<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhslgbbmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:planet" /></template>
<style>
.lhslgbbmu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 13a7.071 7.071 0 1 1 14-2a7.071 7.071 0 0 1-14 2m-.07-1.143c-1.727 1.486-2.763 2.932-2.911 4.067c-.15 1.135.6 1.88 2.104 2.095s3.66-.116 6.062-.93a29.4 29.4 0 0 0 6.975-3.487c2.092-1.433 3.65-2.96 4.382-4.292c.73-1.333.584-2.379-.414-2.94c-.997-.563-2.776-.602-5-.111");
}

</style>

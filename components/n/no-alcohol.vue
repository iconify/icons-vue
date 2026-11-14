<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihcua2esn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:no-alcohol" /></template>
<style>
.ihcua2esn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.773 11.319q-.208-.175-.395-.372t-.353-.413q-.165-.217-.305-.449q-.141-.233-.255-.48t-.202-.504q-.087-.257-.145-.523q-.059-.266-.089-.536T7 7.5L7.25 3h9.5l.017.3M12 15.9v4.6m-3.5 0h7m5-17l-17 17");
}

</style>

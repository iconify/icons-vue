<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hs4b65bzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:music-note-off" /></template>
<style>
.hs4b65bzq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 18C9 19.6569 7.6569 21 6 21C4.3431 21 3 19.6569 3 18C3 16.3431 4.3431 15 6 15C7.6569 15 9 16.3431 9 18ZM18.8715 18.8715C18.5957 18.9551 18.3031 19 18 19C16.3431 19 15 17.6569 15 16C15 15.6969 15.0449 15.4043 15.1285 15.1285M18.7518 13.095C19.8046 13.3666 20.6334 14.1954 20.905 15.2482M9 18L9 9M10.4202 4.7633L21 3L21 15.3431M2 2L22 22");
}

</style>

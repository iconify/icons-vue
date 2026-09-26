<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f8dypr8nz"/><path class="gkoxp2d3b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:podium-3-two-tone" /></template>
<style>
.f8dypr8nz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 22V18.5H9V15H14V11.5H20V22H4Z");
  stroke: none;
}

.gkoxp2d3b {
  d: path("M2 22H22M4 22V18.5H9V15H14V11.5H20V22H4ZM15.3 2H18.7L16.728 4.33402C18.7 4.33402 18.7 4.97056 18.7 5.92539C18.7 7.41067 15.606 7.19849 15.3 6.24366");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

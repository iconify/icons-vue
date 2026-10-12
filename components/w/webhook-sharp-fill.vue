<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="nb7i_bblx"/><path class="n2vyk37td"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:webhook-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.n2vyk37td {
  d: path("M13.3416 7.6833L16.1459 13.2918M16 19L11 19M6.3416 16.3167L9.1459 10.7082");
}

.nb7i_bblx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16 5C16 7.2091 14.2091 9 12 9C9.7909 9 8 7.2091 8 5C8 2.7909 9.7909 1 12 1C14.2091 1 16 2.7909 16 5ZM23 19C23 21.2091 21.2091 23 19 23C16.7909 23 15 21.2091 15 19C15 16.7909 16.7909 15 19 15C21.2091 15 23 16.7909 23 19ZM9 19C9 21.2091 7.2091 23 5 23C2.7909 23 1 21.2091 1 19C1 16.7909 2.7909 15 5 15C7.2091 15 9 16.7909 9 19Z");
  stroke: none;
}

</style>

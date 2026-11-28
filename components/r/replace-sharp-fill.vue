<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="g3j5t4biw"/><path clip-rule="evenodd" class="hd0cwztwb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:replace-sharp-fill" /></template>
<style>
.g3j5t4biw {
  d: path("M12 7H21M17.707 10.2929L21 7L17.707 3.7071M12 17H3M6.293 20.2929L3 17L6.293 13.7071");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hd0cwztwb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 3C8.209 3 10 4.7909 10 7C10 9.2091 8.209 11 6 11C3.791 11 2 9.2091 2 7C2 4.7909 3.791 3 6 3ZM15 13H21C21.552 13 22 13.4477 22 14V20C22 20.5523 21.552 21 21 21H15C14.448 21 14 20.5523 14 20V14C14 13.4477 14.448 13 15 13Z");
  stroke: none;
}

</style>

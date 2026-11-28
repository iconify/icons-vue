<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pxy54kblv"/><path clip-rule="evenodd" class="a6kqstbkx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:replace-fill" /></template>
<style>
.a6kqstbkx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 3C8.209 3 10 4.7909 10 7C10 9.2091 8.209 11 6 11C3.791 11 2 9.2091 2 7C2 4.7909 3.791 3 6 3ZM16 13H20C21.105 13 22 13.8954 22 15V19C22 20.1046 21.105 21 20 21H16C14.895 21 14 20.1046 14 19V15C14 13.8954 14.895 13 16 13Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pxy54kblv {
  d: path("M13 7H21M18 10L21 7L18 4M11 17H3M6 20L3 17L6 14");
}

</style>

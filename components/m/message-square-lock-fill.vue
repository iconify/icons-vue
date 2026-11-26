<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="xp0bjzryk"/><path class="dt5sxgbvt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-lock-fill" /></template>
<style>
.dt5sxgbvt {
  d: path("M15 16L20 16C20.5523 16 21 16.4477 21 17L21 20C21 20.5523 20.5523 21 20 21L15 21C14.4477 21 14 20.5523 14 20L14 17C14 16.4477 14.4477 16 15 16ZM15.5 16L15.5 14C15.5 12.8954 16.3954 12 17.5 12C18.6046 12 19.5 12.8954 19.5 14L19.5 16");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xp0bjzryk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 2L18 2C20.2091 2 22 3.7909 22 6L22 8C22 8.5523 21.5523 9 21 9L14 9C12.3431 9 11 10.3431 11 12L11 17C11 17.5523 10.5523 18 10 18L7.4142 18L3.7071 21.7071C3.5196 21.8946 3.2652 22 3 22C2.4477 22 2 21.5523 2 21L2 6C2 3.7909 3.7909 2 6 2Z");
  stroke: none;
}

</style>

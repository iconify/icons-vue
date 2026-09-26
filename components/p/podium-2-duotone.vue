<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="csm16okln"/><path class="ycd51yi5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:podium-2-duotone" /></template>
<style>
.csm16okln {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 10.5C20.5523 10.5 21 10.9477 21 11.5V22C21 22.5523 20.5523 23 20 23H4C3.44772 23 3 22.5523 3 22V18.5C3 17.9477 3.44772 17.5 4 17.5H8V15C8 14.4477 8.44772 14 9 14H13V11.5C13 10.9477 13.4477 10.5 14 10.5H20Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ycd51yi5l {
  d: path("M2 22H22M15.3 3.4C15.3 2.3 16.116 2 17 2C17.884 2 18.7 2.5 18.7 3.5C18.7 4.9 15.3 6.3 15.3 7H18.7");
}

</style>

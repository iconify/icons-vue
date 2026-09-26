<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="csm16okln"/><path class="e-2ns768c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:podium-3-sharp-duotone" /></template>
<style>
.csm16okln {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 10.5C20.5523 10.5 21 10.9477 21 11.5V22C21 22.5523 20.5523 23 20 23H4C3.44772 23 3 22.5523 3 22V18.5C3 17.9477 3.44772 17.5 4 17.5H8V15C8 14.4477 8.44772 14 9 14H13V11.5C13 10.9477 13.4477 10.5 14 10.5H20Z");
  stroke: none;
}

.e-2ns768c {
  d: path("M1 22H23M14.3 2H18.7L16.728 4.334C18.7 4.334 18.7 4.9706 18.7 5.9254C18.7 7.4107 15.606 7.1985 15.3 6.2437L14.9948 5.2914");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

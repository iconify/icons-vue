<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="toy11acjo"/><path class="ae9hjf2kz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:washing-machine-off-sharp-two-tone" /></template>
<style>
.ae9hjf2kz {
  d: path("M20 20L20 22L4 22L4 4M15.6465 15.6465C15.0188 17.0343 13.6222 18 12 18C9.7909 18 8 16.2091 8 14C8 12.3778 8.9657 10.9812 10.3535 10.3535M1.7071 1.7071L22.2929 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.toy11acjo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M21 21L21 22C21 22.5523 20.5523 23 20 23L4 23C3.4477 23 3 22.5523 3 22L3 3L21 21ZM4.7426 1L20 1C20.5523 1 21 1.4477 21 2L21 17.2574L4.7426 1Z");
  stroke: none;
}

</style>

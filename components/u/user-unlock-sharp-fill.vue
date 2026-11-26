<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="lx7i4eb2p"/><path class="jpdhonkoa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-unlock-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jpdhonkoa {
  d: path("M15 16L22 16L22 21L15 21ZM20.5 16L20.5 12C20.5 10.8954 19.6046 10 18.5 10C17.3954 10 16.5 10.8954 16.5 12L16.5 13");
}

.lx7i4eb2p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 13C10.3396 13 10.6733 13.0255 11 13.0723L11 22L2 22C1.4477 22 1 21.5523 1 21L1 20C1 16.134 4.134 13 8 13ZM9 3C11.2092 3 13 4.7908 13 7C13 9.2092 11.2092 11 9 11C6.7909 11 5 9.2092 5 7C5 4.7908 6.7909 3 9 3Z");
  stroke: none;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="d69y9rbur"/><path class="vnhzefb8d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-lock-sharp-fill" /></template>
<style>
.d69y9rbur {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 2L21 2C21.5523 2 22 2.4477 22 3L22 8C22 8.5523 21.5523 9 21 9L11 9L11 17C11 17.5523 10.5523 18 10 18L7.4142 18L3.7071 21.7071C3.5196 21.8946 3.2652 22 3 22C2.4477 22 2 21.5523 2 21L2 3C2 2.4477 2.4477 2 3 2Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vnhzefb8d {
  d: path("M14 16L21 16L21 21L14 21ZM15.5 16L15.5 14C15.5 12.8954 16.3954 12 17.5 12C18.6046 12 19.5 12.8954 19.5 14L19.5 16");
}

</style>

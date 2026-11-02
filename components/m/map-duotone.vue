<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="d1-zedcrm"/><path class="rgn-eqb0a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:map-duotone" /></template>
<style>
.d1-zedcrm {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 18a1 1 0 0 1-.553.894l-4 2c-.356.181-.75.274-1.149.273C3.076 21.164 2 20.265 2 19V7c.001-1.348 1.478-2.357 2.553-2.894l4-2A1 1 0 0 1 10 3Zm8.553-14.894c.356-.181.75-.274 1.149-.273C20.924 2.836 22 3.735 22 5v12c-.001 1.348-1.478 2.357-2.553 2.894l-4 2A1 1 0 0 1 14 21V6c0-.379.214-.725.553-.894Z");
}

.ft5dv1b6b {
  fill: none;
}

.rgn-eqb0a {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m9 3l6 3l4-2c.919-.46 2 .081 2 1v12c0 .613-.774 1.387-2 2l-4 2l-6-3l-4 2c-.919.46-2-.081-2-1V7c0-.613.774-1.387 2-2zm0 0v15m6-12v15");
}

</style>

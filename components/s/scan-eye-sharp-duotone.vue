<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="m-rom16pb"/><path class="vfe68gboq"/><path clip-rule="evenodd" class="brz0lacck"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scan-eye-sharp-duotone" /></template>
<style>
.brz0lacck {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.0164 11.8197C5.6345 8.4485 8.5726 6 12 6C15.4274 6 18.3655 8.4485 18.9836 11.8197C18.9945 11.8792 19 11.9395 19 12C19 12.0605 18.9945 12.1208 18.9836 12.1803C18.3655 15.5515 15.4274 18 12 18C8.5726 18 5.6345 15.5515 5.0164 12.1803C5.0055 12.1208 5 12.0605 5 12C5 11.9395 5.0055 11.8792 5.0164 11.8197ZM13.5 12C13.5 11.1716 12.8284 10.5 12 10.5C11.1716 10.5 10.5 11.1716 10.5 12C10.5 12.8284 11.1716 13.5 12 13.5C12.8284 13.5 13.5 12.8284 13.5 12Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.m-rom16pb {
  stroke-opacity: 0.4;
  d: path("M3 9L3 3L9 3M15 3L21 3L21 9M21 15L21 21L15 21M9 21L3 21L3 15");
}

.vfe68gboq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13.5 12C13.5 11.1716 12.8284 10.5 12 10.5C11.1716 10.5 10.5 11.1716 10.5 12C10.5 12.8284 11.1716 13.5 12 13.5C12.8284 13.5 13.5 12.8284 13.5 12Z");
  stroke: none;
}

</style>

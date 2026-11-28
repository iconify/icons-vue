<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="vhztpbc5s"/><path class="rb8wnqlyb"/><path class="ahhqo1b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scan-box-off-sharp-duotone" /></template>
<style>
.ahhqo1b4s {
  d: path("M1.7071 1.7071L22.2929 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rb8wnqlyb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 12L13 12L13 17C13 17.3444 12.8228 17.6646 12.5309 17.8474C12.2391 18.0303 11.8737 18.0501 11.5638 17.8998L6.5638 15.4759C6.219 15.3088 6 14.9593 6 14.5761L6 9.4239C6 9.0407 6.219 8.6911 6.5639 8.524L8.1966 7.7328L8.9605 9.3091L12.458 11.1111ZM12.8113 6.282L17.4362 8.5241C17.781 8.6912 18 9.0407 18 9.4239L18 12.3431L16 12.3431L16 10.0504L11.9389 8.0816Z");
  stroke: none;
}

.vhztpbc5s {
  stroke-opacity: 0.4;
  d: path("M3 9L3 3M21 21L15 21M9 21L3 21L3 15M15 3L21 3L21 9");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="xskf5vaoq"/><path class="rtw5fkfor"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:upload-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rtw5fkfor {
  d: path("M12 15L12 3M7.7071 7.2929L12 3L16.2929 7.2929");
}

.xskf5vaoq {
  stroke-opacity: 0.4;
  d: path("M4 17L4 21L20 21L20 17");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="chd8r9lmu"/><path class="jpdhonkoa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-unlock-sharp-duotone" /></template>
<style>
.chd8r9lmu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 22H2C1.44772 22 1 21.5523 1 21V19C1 15.134 4.13402 12 8 12H12V22ZM9 2C11.2092 2 13 3.7908 13 6C13 8.2092 11.2092 10 9 10C6.7909 10 5 8.2092 5 6C5 3.7908 6.7909 2 9 2Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jpdhonkoa {
  d: path("M15 16L22 16L22 21L15 21ZM20.5 16L20.5 12C20.5 10.8954 19.6046 10 18.5 10C17.3954 10 16.5 10.8954 16.5 12L16.5 13");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="fi3zdpjpg"/><path class="b_oy6yvje"/><path clip-rule="evenodd" class="jy2azbbyr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:radius-sharp-two-tone" /></template>
<style>
.b_oy6yvje {
  d: path("M12 2.5L12 12");
}

.fi3zdpjpg {
  stroke-opacity: 0.4;
  d: path("M15.68 2.7018C19.4945 4.2114 22 7.8977 22 12C22 17.5228 17.5228 22 12 22C6.4772 22 2 17.5228 2 12C2 7.8977 4.5055 4.2114 8.32 2.7018");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jy2azbbyr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.5 2.5C13.5 3.3284 12.8284 4 12 4C11.1716 4 10.5 3.3284 10.5 2.5C10.5 1.6716 11.1716 1 12 1C12.8284 1 13.5 1.6716 13.5 2.5ZM13.5 12C13.5 12.8284 12.8284 13.5 12 13.5C11.1716 13.5 10.5 12.8284 10.5 12C10.5 11.1716 11.1716 10.5 12 10.5C12.8284 10.5 13.5 11.1716 13.5 12Z");
  stroke: none;
}

</style>

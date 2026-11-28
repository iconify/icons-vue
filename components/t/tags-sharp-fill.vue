<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="kv9hvgb4h"/><path class="tdzrgtbid"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tags-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kv9hvgb4h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.741 9.7427L22.741 14.1569C22.9077 14.3408 23 14.5802 23 14.8284C23 15.0936 22.8946 15.348 22.7071 15.5355L15.5355 22.7071C15.348 22.8946 15.0936 23 14.8284 23C14.5802 23 14.3408 22.9077 14.1569 22.741L5.3285 14.741C5.1193 14.5515 5 14.2823 5 14L5 6C5 5.4477 5.4477 5 6 5L14 5C14.2823 5 14.5515 5.1193 14.741 5.3285ZM12.5 11C12.5 10.1716 11.8284 9.5 11 9.5C10.1716 9.5 9.5 10.1716 9.5 11C9.5 11.8284 10.1716 12.5 11 12.5C11.8284 12.5 12.5 11.8284 12.5 11Z");
  stroke: none;
}

.tdzrgtbid {
  d: path("M2 10L2 2L10 2");
}

</style>

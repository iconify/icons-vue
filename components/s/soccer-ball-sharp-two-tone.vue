<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="t8drw368i"/><path class="xfq7fqb3g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:soccer-ball-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t8drw368i {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 12C23 18.0751 18.0751 23 12 23C5.9249 23 1 18.0751 1 12C1 5.9249 5.9249 1 12 1C18.0751 1 23 5.9249 23 12Z");
  stroke: none;
}

.xfq7fqb3g {
  d: path("M22 12C22 17.5228 17.5228 22 12 22C6.4772 22 2 17.5228 2 12C2 6.4772 6.4772 2 12 2C17.5228 2 22 6.4772 22 12ZM14.9389 7.9549L16.7553 13.5451L12 17L7.2447 13.5451L9.0611 7.9549L14.9389 7.9549ZM14.9389 7.9549L17.8779 3.9098M16.7553 13.5451L21.5106 15.0902M12 17L12 22M7.2447 13.5451L2.4894 15.0902M9.0611 7.9549L6.1221 3.9098");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="rqh4y-aib"/><path class="xv2bvdxhy"/><path class="k8te4qbon"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:temperature-quarter-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.k8te4qbon {
  fill: currentColor;
  d: path("M13.5 16C13.5 16.8284 12.8284 17.5 12 17.5C11.1716 17.5 10.5 16.8284 10.5 16C10.5 15.1716 11.1716 14.5 12 14.5C12.8284 14.5 13.5 15.1716 13.5 16Z");
  stroke: none;
}

.rqh4y-aib {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 6C7 3.2386 9.2386 1 12 1C14.7614 1 17 3.2386 17 6L17 11.101C18.282 12.4094 19 14.1682 19 16C19 19.866 15.866 23 12 23C8.134 23 5 19.866 5 16C5 14.1682 5.718 12.4094 7 11.101L7 6Z");
  stroke: none;
}

.xv2bvdxhy {
  d: path("M8 6C8 3.7909 9.7909 2 12 2C14.2091 2 16 3.7909 16 6L16 11.5279C17.2726 12.6661 18 14.2926 18 16C18 19.3137 15.3137 22 12 22C8.6863 22 6 19.3137 6 16C6 14.2926 6.7274 12.6661 8 11.5279L8 6ZM12 16L12 11L12 10");
}

</style>

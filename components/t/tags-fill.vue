<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="any5_ab-g"/><path class="nx87xgb-j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tags-fill" /></template>
<style>
.any5_ab-g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.7071 9.2929L22.1213 12.7071C23.2928 13.8786 23.2928 15.7782 22.1213 16.9497L16.9497 22.1213C15.7782 23.2928 13.8786 23.2928 12.7071 22.1213L5.8787 15.2929C5.3161 14.7303 5 13.9672 5 13.1716L5 9C5 6.7908 6.7908 5 9 5L13.1716 5C13.9672 5 14.7303 5.3161 15.2929 5.8787ZM12.5 11C12.5 10.1716 11.8284 9.5 11 9.5C10.1716 9.5 9.5 10.1716 9.5 11C9.5 11.8284 10.1716 12.5 11 12.5C11.8284 12.5 12.5 11.8284 12.5 11Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nx87xgb-j {
  d: path("M2 9L2 5C2 3.3431 3.3431 2 5 2L9 2");
}

</style>

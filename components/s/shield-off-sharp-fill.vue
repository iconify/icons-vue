<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="y7e625bep"/><path class="qib3ujb7r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shield-off-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qib3ujb7r {
  d: path("M1.707 1.707L22.293 22.293");
}

.y7e625bep {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.852 18.852C17.567 20.311 15.649 21.882 13.175 22.791C12.417 23.07 11.583 23.07 10.825 22.791C7.967 21.741 5.852 19.808 4.597 18.185L3.209 16.389C3.073 16.214 3 15.999 3 15.778V5.309C3 4.802 3.379 4.376 3.882 4.316L4.27 4.27L18.852 18.852ZM7.282 3.626C8.576 3.122 9.582 2.379 10.328 1.655C11.229 0.782 12.771 0.782 13.672 1.655C14.8 2.75 16.523 3.889 18.935 4.175L20.118 4.316C20.621 4.376 21 4.802 21 5.309V15.778C21 15.999 20.927 16.215 20.791 16.39L20.466 16.81L7.282 3.626Z");
  stroke: none;
}

</style>

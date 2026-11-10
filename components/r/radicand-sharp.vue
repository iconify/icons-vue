<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cso2d_sbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:radicand-sharp" /></template>
<style>
.cso2d_sbu {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M1.555 14.3L5 12L9.318 20L14.034 4H23M15.707 11.71L19 15M19 15L22.293 18.29M19 15L22.293 11.71M19 15L15.707 18.29");
}

</style>

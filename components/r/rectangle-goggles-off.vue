<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_ma5w08w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:rectangle-goggles-off" /></template>
<style>
.a_ma5w08w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11.6569 6L20 6C21.1046 6 22 6.8954 22 8L22 16C22 16.1082 21.9914 16.2144 21.9749 16.318M18 18L16.9612 18C16.3537 18 15.7791 17.7238 15.3995 17.2494L12.7809 13.9761C12.3805 13.4757 11.6195 13.4757 11.2191 13.9761L8.60049 17.2494C8.2209 17.7238 7.6463 18 7.03875 18L4 18C2.8954 18 2 17.1046 2 16L2 8C2 6.8954 2.8954 6 4 6L6 6M2 2L22 22");
}

</style>

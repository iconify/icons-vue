<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wiouwht_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sunglasses-sharp" /></template>
<style>
.wiouwht_z {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.2127 15.9743L15.3334 19L22 19L22 13L14.5479 13C13.8514 13 13.3682 13.6942 13.6101 14.3473ZM9.7873 15.9743L8.6666 19L2 19L2 13L9.4521 13C10.1486 13 10.6318 13.6942 10.3899 14.3473ZM2 13.5L4.2924 7.6512C4.7424 6.601 5.6202 5.7933 6.7041 5.432L8 5L8.154 4.9487M22 13.5L19.7076 7.6512C19.2576 6.601 18.3798 5.7933 17.2959 5.432L16 5L15.846 4.9487M14.2127 15.9743C13.1111 15 10.8889 15 9.7873 15.9743");
}

</style>

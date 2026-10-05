<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2ipz-bdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sunglasses" /></template>
<style>
.o2ipz-bdo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.2127 15.9743L15.0917 18.3473C15.237 18.7396 15.6111 19 16.0294 19L20 19C21.1046 19 22 18.1046 22 17L22 14C22 13.4477 21.5523 13 21 13L14.5479 13C13.8514 13 13.3682 13.6942 13.6101 14.3473ZM9.7873 15.9743L8.9083 18.3473C8.763 18.7396 8.3889 19 7.9706 19L4 19C2.8954 19 2 18.1046 2 17L2 14C2 13.4477 2.4477 13 3 13L9.4521 13C10.1486 13 10.6318 13.6942 10.3899 14.3473ZM2 13.5L4.2924 7.6512C4.7424 6.601 5.6202 5.7933 6.7041 5.432L8 5M22 13.5L19.7076 7.6512C19.2576 6.601 18.3798 5.7933 17.2959 5.432L16 5M14.2127 15.9743C13.1111 15 10.8889 15 9.7873 15.9743");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="v0wkaub9o"/><path class="zhbmsgb3y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wheelchair-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v0wkaub9o {
  d: path("M9 8L9 15L16 15L18 21L22 21M9 11L14 11M13.9216 18.5744L13.209 19.276C12.126 20.3422 10.6398 21 9 21C5.6863 21 3 18.3137 3 15C3 13.223 3.7725 11.6264 5 10.5278L5.7451 9.8609");
}

.zhbmsgb3y {
  fill: currentColor;
  d: path("M12 4C12 5.1046 11.1046 6 10 6C8.8954 6 8 5.1046 8 4C8 2.8954 8.8954 2 10 2C11.1046 2 12 2.8954 12 4Z");
  stroke: none;
}

</style>

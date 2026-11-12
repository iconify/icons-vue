<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="f6zwjsbcc"/><path class="pmzn7ofxe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:route-broken" /></template>
<style>
.f6zwjsbcc {
  d: path("M17.8575 6.14204C20.6189 8.90341 21.9996 10.2841 21.9996 11.9998C21.9996 13.7155 20.6189 15.0961 17.8575 17.8575L17.8575 17.8575L17.8575 17.8575C15.0961 20.6189 13.7155 21.9996 11.9998 21.9996C10.2841 21.9996 8.90341 20.6189 6.14204 17.8575C3.38068 15.0962 2 13.7155 2 11.9998C2 10.2841 3.38068 8.90341 6.14204 6.14204C8.90341 3.38068 10.2841 2 11.9998 2C13.1406 2 14.1332 2.61041 15.4821 3.83123");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pmzn7ofxe {
  stroke-linejoin: round;
  d: path("M9 14C9 13.0572 9 12.5858 9.29289 12.2929C9.58579 12 10.0572 12 11 12H15M13 14L15 12L13 10");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="rc8m91b3b"/><path class="xsdyvcash"/><path class="puh-h6bmr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:opacity-broken" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.puh-h6bmr {
  d: path("M7.64209 10.7594C8.68441 9.27206 9.91704 7.84913 11.0088 6.68774");
}

.rc8m91b3b {
  d: path("M20.5442 13.9702C20.5442 13.9702 17.3062 16.0608 12.064 16.0608C6.82184 16.0608 3.4541 13.9758 3.4541 13.9758");
}

.xsdyvcash {
  d: path("M6.18106 19.6353C7.71126 21.1034 9.75458 22 11.9989 22C16.7431 22 20.5889 17.9939 20.5889 13.0521C20.5889 9.96011 17.2261 5.83321 14.7086 3.17693C13.2182 1.60443 10.7796 1.60443 9.28928 3.17693C6.77177 5.83321 3.40894 9.96011 3.40894 13.0521C3.40894 14.066 3.5708 15.0404 3.86909 15.949");
}

</style>

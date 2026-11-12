<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ilavvohjs"/><path class="ccd15mqzm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rotate-anticlockwise-2-broken" /></template>
<style>
.ccd15mqzm {
  d: path("M10.9289 14.9289C12.3096 13.5482 13 12.8579 13 12C13 11.4039 12.6667 10.8887 12 10.1665C11.7073 9.8494 11.3502 9.4924 10.9289 9.0711C10.5076 8.6498 10.1506 8.2927 9.8335 8C9.1113 7.3333 8.5961 7 8 7C7.1421 7 6.4518 7.6904 5.0711 9.0711C3.6904 10.4518 3 11.1421 3 12C3 12.8579 3.6904 13.5482 5.0711 14.9289C6.4518 16.3096 7.1421 17 8 17C8.8579 17 9.5482 16.3096 10.9289 14.9289Z");
}

.ilavvohjs {
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16 7.4286V4H19.75M16 4C19.125 6.8571 21 9 21 12C21 13.3312 20.655 14.7186 19.9874 16M16 20C16.7468 19.6058 17.4145 19.1285 18 18.5907");
}

.jx0p4fbya {
  fill: none;
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="s73g0l4am"/><path class="l1whkcbis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:send-fast-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.l1whkcbis {
  d: path("M1.7071 22.2929L6.7929 17.2071M1.7071 16.2929L5.7929 12.2071M7.7071 22.2929L11.7929 18.2071");
}

.s73g0l4am {
  fill: currentColor;
  d: path("M22.9589 2.2837L18.2391 18.236C18.1134 18.6608 17.7232 18.9523 17.2802 18.9523C16.9498 18.9523 16.6407 18.7891 16.4543 18.5162L12.864 13.2573L17.3615 6.6385L10.7427 11.136L5.4838 7.5457C5.2109 7.3593 5.0477 7.0502 5.0477 6.7198C5.0477 6.2768 5.3392 5.8866 5.764 5.7609L21.7163 1.0411C21.8084 1.0138 21.9039 1 22 1C22.5523 1 23 1.4477 23 2C23 2.0961 22.9862 2.1916 22.9589 2.2837Z");
  stroke: none;
}

</style>

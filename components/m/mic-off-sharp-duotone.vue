<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="uz0j13afx"/><path class="wnohalbyc"/><path class="ahhqo1b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mic-off-sharp-duotone" /></template>
<style>
.ahhqo1b4s {
  d: path("M1.7071 1.7071L22.2929 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uz0j13afx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 15C9.7909 15 8 13.2091 8 11V8L14.2841 14.2841C13.6365 14.7354 12.8492 15 12 15ZM8.1508 3.9081C8.626 2.2297 10.1694 1 12 1C14.2091 1 16 2.7909 16 5L16 11C16 11.2377 15.9793 11.4705 15.9395 11.6968Z");
  stroke: none;
}

.wnohalbyc {
  stroke-opacity: 0.4;
  d: path("M16.4246 16.4246C15.2187 17.4094 13.6783 18 12 18M12 18C8.134 18 5 14.866 5 11L5 10M12 18L12 22M7 22L17 22");
}

</style>

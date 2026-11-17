<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="w_uutqbms"/><path class="hpmdrsbdp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:map-pin-radius-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hpmdrsbdp {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 16.857C9.857 15.43 7 12.571 7 9a5 5 0 0 1 10 0c0 3.571-2.857 6.429-5 7.857M11 9a1 1 0 1 0 2 0a1 1 0 0 0-2 0m-6 7c-2.18.92-2.616 2.185-1.121 3.253C5.373 20.32 8.532 21 12 21s6.627-.68 8.121-1.747S21.18 16.92 19 16");
}

.w_uutqbms {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 16.857C9.415 15.133 7.003 12.253 7 9a5 5 0 0 1 10 0c-.003 3.253-2.415 6.133-5 7.857");
}

</style>

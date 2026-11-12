<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="si_mtzbvj"/><path class="txk_m_bon"/><path class="eveg1sbcl"/><path class="ns0fhccwl"/><path class="s6le__b7v"/><path class="wf-yddc_g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:socket-broken" /></template>
<style>
.eveg1sbcl {
  d: path("M12 18.0001V16.5");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ns0fhccwl {
  d: path("M12 7.5V6");
}

.s6le__b7v {
  stroke-linejoin: round;
  d: path("M10 12H10.0001");
}

.si_mtzbvj {
  d: path("M22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C21.5093 4.43821 21.8356 5.80655 21.9449 8");
}

.txk_m_bon {
  d: path("M6.58447 9.41299C6.87047 8.81431 7.2614 8.25323 7.75727 7.75736C10.1004 5.41421 13.8994 5.41421 16.2426 7.75736C18.5857 10.1005 18.5857 13.8995 16.2426 16.2426C13.8994 18.5858 10.1004 18.5858 7.75727 16.2426C7.2614 15.7468 6.87047 15.1857 6.58447 14.587");
}

.wf-yddc_g {
  stroke-linejoin: round;
  d: path("M14 12H14.0001");
}

</style>

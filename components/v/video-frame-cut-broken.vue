<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="k2khccbcd"/><path class="fenutzb3t"/><path class="h14wliw7l"/><path class="e9fgc-b_d"/><path class="i9nr5tbkn"/><path class="m5dtgkbek"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:video-frame-cut-broken" /></template>
<style>
.e9fgc-b_d {
  d: path("M3 8.5L7 8.5M17 8.5H21");
}

.fenutzb3t {
  d: path("M12 2V3.66667M12 22V20.3333M12 7V10.3333M12 13.6667V17");
}

.h14wliw7l {
  d: path("M7 3.5V20.5");
}

.i9nr5tbkn {
  d: path("M17 15.5H21M3 15.5H5.75L7 15.5");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k2khccbcd {
  d: path("M17 3.5V20.5");
}

.m5dtgkbek {
  stroke-linejoin: round;
  d: path("M14.5 3.00293C17.2939 3.02331 18.8237 3.16641 19.8284 4.17112C20.8916 5.23426 20.99 6.8854 20.9991 10M14.5 20.9962C17.2939 20.9758 18.8237 20.8327 19.8284 19.828C20.8916 18.7648 20.99 17.1137 20.9991 13.9991M9.49991 20.9962C6.70609 20.9758 5.17627 20.8327 4.17157 19.828C3 18.6564 3 16.7708 3 12.9995V10.9995C3 7.22831 3 5.34269 4.17157 4.17112C5.17627 3.16642 6.70609 3.02331 9.49991 3.00293");
}

</style>

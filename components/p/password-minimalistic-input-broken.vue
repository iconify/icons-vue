<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="om4lnzbpu"/><path class="bpkt4gbdh"/><path class="sp15d0bxe"/><path class="km0rz_boi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:password-minimalistic-input-broken" /></template>
<style>
.bpkt4gbdh {
  d: path("M22 12C22 15.7712 22 17.6569 20.8284 18.8284C19.7653 19.8915 18.1143 19.99 15 19.9991M12 4H10C6.22876 4 4.34315 4 3.17157 5.17157C2 6.34315 2 8.22876 2 12C2 15.7712 2 17.6569 3.17157 18.8284C4.34315 20 6.22876 20 10 20H12M15 4.00093C18.1143 4.01004 19.7653 4.10848 20.8284 5.17157C21.4816 5.82475 21.7706 6.69989 21.8985 8");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.km0rz_boi {
  stroke-linejoin: round;
  d: path("M12 12H12.0001");
}

.om4lnzbpu {
  d: path("M15 2V22");
}

.sp15d0bxe {
  stroke-linejoin: round;
  d: path("M8 12H8.0001");
}

</style>

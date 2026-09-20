<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGnWuzwcez)" class="r4i437pya"/><path class="tiv0_pb0z"/></g><defs><linearGradient id="SVGnWuzwcez" x1="12" x2="12" y1="4.001" y2="19.998" gradientUnits="userSpaceOnUse"><stop class="c9-3dob4j"/><stop offset="1" class="g-04g98fq"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xep-background" /></template>
<style>
.c9-3dob4j {
  stop-color: var(--svg-color--017fee, #017fee);
}

.ft5dv1b6b {
  fill: none;
}

.g-04g98fq {
  stop-color: var(--svg-color--171b6e, #171b6e);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.tiv0_pb0z {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.002 19.999a8 8 0 0 0 7.864-9.459l-1.875 1.1l.01.36a5.999 5.999 0 0 1-10.783 3.624l2.395-1.43a3.248 3.248 0 0 0 5.309-3.169l2.6-1.55l1.669-.974a7.999 7.999 0 1 0-7.189 11.498m-3.45-7.674L6.254 13.7a5.999 5.999 0 0 1 9.978-5.96l-2.45 1.465a3.25 3.25 0 0 0-5.218 3.115zm8.35-3.49l-3.635 2.19v1.6l-1.515.875l-1.325-.765l-3.484 2.094l-.2-.33l3.495-2.1v-1.524L11.752 10l1.26.73l3.69-2.22z");
}

</style>

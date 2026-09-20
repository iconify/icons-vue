<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGnvlSzbar)" class="sh6pww12h"/><path fill="url(#SVGDYP1FeVH)" class="rh9zcbauy"/><defs><linearGradient id="SVGnvlSzbar" x1="9.272" x2="9.272" y1="6" y2="17.999" gradientUnits="userSpaceOnUse"><stop class="v4-w6wtkv"/><stop offset="1" class="f5zzelbzd"/></linearGradient><linearGradient id="SVGDYP1FeVH" x1="18" x2="18" y1="8.998" y2="17.452" gradientUnits="userSpaceOnUse"><stop class="v4-w6wtkv"/><stop offset="1" class="f5zzelbzd"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:uno" /></template>
<style>
.f5zzelbzd {
  stop-color: var(--svg-color--3e3bac, #3e3bac);
}

.ft5dv1b6b {
  fill: none;
}

.rh9zcbauy {
  d: path("M18 8.998a3 3 0 0 0-3 3v5.454h.546v-4.909a1.636 1.636 0 1 1 3.272 0v4.91H21v-5.455a3 3 0 0 0-3-3");
}

.sh6pww12h {
  d: path("M5.182 6H3v7.636a4.363 4.363 0 0 0 4.363 4.363h.546a4.363 4.363 0 0 0 4.363-4.363V6h-2.181v7.363a2.454 2.454 0 0 1-4.91 0zm8.181 3.273h2.182v8.18h-2.182z");
}

.v4-w6wtkv {
  stop-color: var(--svg-color--5079dd, #5079dd);
}

</style>

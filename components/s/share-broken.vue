<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wjw99lb2m"/><path class="nk62zxbpn"/><path class="amsssrbtq"/><path class="ex_z2zb_b"/><path class="d-orjcc8m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:share-broken" /></template>
<style>
.amsssrbtq {
  d: path("M19.1655 6.75042C18.4751 7.94615 16.9461 8.35584 15.7504 7.66548C14.5547 6.97513 14.145 5.44615 14.8354 4.25042C15.5257 3.05469 17.0547 2.645 18.2504 3.33535");
}

.d-orjcc8m {
  d: path("M9.09668 10.6372L14.9039 6.86258");
}

.ex_z2zb_b {
  d: path("M9.09668 13.3628L14.9038 17.1374");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nk62zxbpn {
  d: path("M17 21C18.3807 21 19.5 19.8807 19.5 18.5C19.5 17.1193 18.3807 16 17 16C15.6193 16 14.5 17.1193 14.5 18.5");
}

.wjw99lb2m {
  d: path("M4.5 12C4.5 13.3807 5.61929 14.5 7 14.5C8.38071 14.5 9.5 13.3807 9.5 12C9.5 10.6193 8.38071 9.5 7 9.5");
}

</style>

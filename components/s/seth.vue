<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGWLPVzFzZ)" clip-rule="evenodd" class="qqqa0_gae"/><path class="w4ej5lpjs"/><path class="tj1qbky_w"/><path class="qz-v5ccvz"/><path class="abetvtbqr"/><path class="z5_wsqbxx"/><path class="my70b05lt"/><defs><linearGradient id="SVGWLPVzFzZ" x1="17.029" x2="6.706" y1="5.118" y2="19.147" gradientUnits="userSpaceOnUse"><stop class="st8gekbwu"/><stop offset="1" class="jnwhs4buz"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:seth" /></template>
<style>
.abetvtbqr {
  fill: var(--svg-color--8198ee, #8198ee);
  d: path("M12 13.852v-3.176l3.177 1.323z");
}

.ft5dv1b6b {
  fill: none;
}

.jnwhs4buz {
  stop-color: var(--svg-color--142d44, #142d44);
}

.my70b05lt {
  fill: var(--svg-color--c1ccf7, #c1ccf7);
  d: path("M15.177 12.53L12 14.646v2.647z");
}

.qqqa0_gae {
  fill-rule: evenodd;
  d: path("M12 19.941a7.942 7.942 0 1 0 0-15.883a7.942 7.942 0 0 0 0 15.883M12 21a9 9 0 1 0 0-18a9 9 0 0 0 0 18");
}

.qz-v5ccvz {
  fill: var(--svg-color--c1ccf7, #c1ccf7);
  d: path("M12.002 10.677v-3.97L15.178 12zm0 0L8.825 12l3.177 1.853z");
}

.st8gekbwu {
  stop-color: var(--svg-color--269981, #269981);
}

.tj1qbky_w {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.002 10.677v-3.97L8.825 12z");
}

.w4ej5lpjs {
  fill: var(--svg-color--627eea, #627eea);
  d: path("M12 18.883a6.882 6.882 0 1 0 0-13.765a6.882 6.882 0 0 0 0 13.765");
}

.z5_wsqbxx {
  fill: var(--svg-color--fff, #fff);
  d: path("m12.002 14.647l-3.177-2.118l3.177 4.765z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#tokenBrandedPolygonPos0)" class="u8exp8bpu"/><defs><linearGradient id="tokenBrandedPolygonPos0" x1="1.935" x2="21.021" y1="17.771" y2="6.556" gradientUnits="userSpaceOnUse"><stop class="ljk2jwbie"/><stop offset=".88" class="eohdpevjx"/><stop offset="1" class="qc68bsael"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:polygon-pos" /></template>
<style>
.eohdpevjx {
  stop-color: var(--svg-color--803bdf, #803BDF);
}

.ft5dv1b6b {
  fill: none;
}

.ljk2jwbie {
  stop-color: var(--svg-color--a726c1, #A726C1);
}

.qc68bsael {
  stop-color: var(--svg-color--7b3fe4, #7B3FE4);
}

.u8exp8bpu {
  d: path("m16.85 15.574l4.743-2.706a.8.8 0 0 0 .407-.696V6.76a.8.8 0 0 0-.407-.697L16.85 3.357a.83.83 0 0 0-.814 0l-4.744 2.706a.8.8 0 0 0-.406.697v9.671l-3.327 1.897L4.23 16.43v-3.794l3.327-1.897l2.194 1.252V9.446l-1.787-1.02a.83.83 0 0 0-.814 0l-4.744 2.706A.8.8 0 0 0 2 11.83v5.412c0 .286.155.552.407.696l4.744 2.706a.83.83 0 0 0 .814 0l4.744-2.706a.8.8 0 0 0 .406-.696V7.569l.06-.033l3.266-1.863l3.327 1.896v3.795L16.44 13.26l-2.191-1.248v2.545l1.784 1.017a.83.83 0 0 0 .814 0z");
}

</style>

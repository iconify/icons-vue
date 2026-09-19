<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="cyfm41bxu"/><path class="hha-e3iim"/></g><g class="y9tr6bcfx"><circle class="zms5a9b7c"/><path class="gxzcmjb8w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pcloud-pass" /></template>
<style>
.cyfm41bxu {
  d: path("M36.05 24.174c.192-6.69-5.076-12.27-11.767-12.463s-12.27 5.076-12.463 11.767a12 12 0 0 0 0 .696");
}

.gxzcmjb8w {
  d: path("M32 28.182v-3.508h0h-8.989m6.687 2.023v-2.023");
}

.hha-e3iim {
  d: path("M13.242 18.115a9.1 9.1 0 0 0 .358 18.18h24a5.84 5.84 0 0 0 3.48-10.53h.05a6 6 0 0 0 .24-1.59a5.85 5.85 0 0 0-5.85-5.85q-.377.01-.75.063");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zms5a9b7c {
  cx: 19.508px;
  cy: 24.674px;
  r: 3.508px;
}

</style>

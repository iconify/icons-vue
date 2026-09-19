<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fin_v4brt"/><path class="f6h0tqbeh"/><circle class="uq3fy3h8c"/><path class="o8jcfw-pd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:secure-tan" /></template>
<style>
.f6h0tqbeh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.582 19.241v-4.363c.017-5.75 4.692-10.396 10.441-10.378c5.724.018 10.36 4.654 10.378 10.378v4.363");
}

.fin_v4brt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.16 19.241h27.68a1.9 1.9 0 0 1 1.901 1.9V41.6a1.9 1.9 0 0 1-1.9 1.9H10.16a1.9 1.9 0 0 1-1.901-1.9V21.142a1.9 1.9 0 0 1 1.9-1.9");
}

.o8jcfw-pd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 31.918v3.675");
}

.uq3fy3h8c {
  cx: 23.991px;
  cy: 27.367px;
  r: 4.037px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

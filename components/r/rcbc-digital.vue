<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oo404_j5f"/><path class="dlewy9o_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rcbc-digital" /></template>
<style>
.dlewy9o_g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.084 29.207v-7.038h2.304c1.303 0 2.359 1.058 2.359 2.363s-1.056 2.364-2.359 2.364h-2.304m2.304 0l2.304 2.309m6.573-2.359v.03a2.331 2.331 0 1 1-4.662 0V24.5a2.331 2.331 0 1 1 4.662 0v.029M43.5 26.846v.03a2.331 2.331 0 1 1-4.662 0V24.5a2.331 2.331 0 1 1 4.662 0v.029m-8.34 1.159a1.76 1.76 0 1 1 0 3.518h-2.903V22.17h2.903a1.76 1.76 0 1 1 0 3.519m0-.001h-2.903");
}

.oo404_j5f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.45 19.637v-4.304L19.42 6.7L4.546 15.287L4.5 32.754L19.42 41.3l15.076-8.452v-1.109");
}

</style>

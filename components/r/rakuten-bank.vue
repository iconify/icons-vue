<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="k4m01p4de"/><path class="fr0wpobui"/><path class="gq567ybfa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rakuten-bank" /></template>
<style>
.fr0wpobui {
  d: path("M43.827 37.003a7 7 0 1 1-14 0a7 7 0 0 1 14 0");
}

.gq567ybfa {
  d: path("m39.427 33.34l-2.6 4l-2.6-4m2.6 8v-4m-2.5 0h5m-5 2h5");
}

.k4m01p4de {
  d: path("M12.308 30.553V3.997h8.874c5.12 0 9.216 3.983 9.216 8.962s-4.096 8.963-9.216 8.963h-8.874m9.208-.008l8.54 8.307m-.14 7.691l-20.47 3.091l-5.273-4.688h25.721");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

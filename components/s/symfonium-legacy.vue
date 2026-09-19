<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="n1t6p0iur"/><path class="d7zc_fbcq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:symfonium-legacy" /></template>
<style>
.d7zc_fbcq {
  d: path("M6.73 22.82h3.355l2.015 3.49l1.898-4.847l2.635 6.309l1.757-7.188l4.073 8.066l2.954-15.732l3.754 22.44l3.035-16.451l2.395 8.066l1.917-6.708l1.515 2.606h3.237");
}

.n1t6p0iur {
  d: path("M13.616 19.637A9.7 9.7 0 0 1 12 14.261h0c0-5.391 4.37-9.76 9.76-9.76h5.743c4.172 0 7.17 1.159 9.562 4.272M12.772 39.227c2.391 3.113 5.39 4.273 9.562 4.273h5.774c5.373 0 9.729-4.356 9.729-9.729v-.042a9.7 9.7 0 0 0-1.697-5.492");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

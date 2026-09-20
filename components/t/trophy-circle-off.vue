<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="k6_fj4bkr"/><path clip-rule="evenodd" class="o56rf4brv"/><path clip-rule="evenodd" class="hq005xbxl"/><path clip-rule="evenodd" class="byip-3bme"/><path clip-rule="evenodd" class="ns4xoabkk"/><path class="t_j776bmu"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:trophy-circle-off" /></template>
<style>
.byip-3bme {
  fill-rule: evenodd;
  d: path("M5.268 7.512a1.003 1.003 0 0 1 1.135.848l.07.489a3.165 3.165 0 0 0 2.62 2.667l-.328 1.968a5.17 5.17 0 0 1-4.277-4.356l-.07-.488a.997.997 0 0 1 .85-1.128m12.311.988a1 1 0 0 0 1 1h2.01a1 1 0 1 0 0-2h-2.01a1 1 0 0 0-1 1");
}

.cuyn6tgcc {
  fill: currentColor;
}

.hq005xbxl {
  fill-rule: evenodd;
  d: path("M11.058 19.5a2.78 2.78 0 0 1 3.786 0zm4.91-1a4.277 4.277 0 0 0-6.033 0l-.796.791c-.632.63-.187 1.709.706 1.709h6.212c.893 0 1.338-1.08.706-1.709zm-7.547-10a1 1 0 0 1-1 1h-2.01a1 1 0 0 1 0-2h2.01a1 1 0 0 1 1 1");
}

.k6_fj4bkr {
  fill-rule: evenodd;
  d: path("M16.675 7.5H9.227l.635 4.418c1.222 2.623 4.956 2.623 6.178 0zm-7.448-2a2 2 0 0 0-1.98 2.285l.64 4.446q.037.256.144.492c1.925 4.217 7.915 4.217 9.84 0q.107-.236.144-.492l.64-4.446a2 2 0 0 0-1.98-2.285z");
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.ns4xoabkk {
  fill-rule: evenodd;
  d: path("M20.732 7.512a1.003 1.003 0 0 0-1.135.848l-.07.489a3.17 3.17 0 0 1-2.62 2.667l.328 1.968a5.17 5.17 0 0 0 4.277-4.356l.07-.488a.997.997 0 0 0-.85-1.128");
}

.o56rf4brv {
  fill-rule: evenodd;
  d: path("M11.95 18.5v-3h2v3z");
}

.t_j776bmu {
  d: path("M4.293 5.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>

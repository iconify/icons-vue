<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ff6feqbvy"/><path class="d-xw3-ouf"/><path class="jjrensbqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:throne" /></template>
<style>
.d-xw3-ouf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.738 39.36a32140 32140 0 0 1-20.88-21.892c-.564-.59-1.543-.037-1.328.75l5.681 20.832a3.523 3.523 0 0 0 4.423 2.447c3.32-1.01 8.376-2.3 12.104-2.138Z");
}

.ff6feqbvy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.836 35.274l9.062-9.502c.536-.562.66-1.401.308-2.094l-8.542-16.82a.928.928 0 0 0-1.656 0l-8.541 16.82a1.83 1.83 0 0 0 .308 2.094z");
}

.jjrensbqi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.835 35.273c4.765-4.992 13.233-13.535 17.307-17.805c.565-.59 1.542-.038 1.328.749l-5.283 20.072a3.52 3.52 0 0 1-4.422 2.445a64 64 0 0 0-5.306-1.384");
}

</style>

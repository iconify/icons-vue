<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q_w7xlb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:totalplay" /></template>
<style>
.q_w7xlb1f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39.64 23.098l-7.997-4.617a1.041 1.041 0 0 0-1.562.901v9.235a1.041 1.041 0 0 0 1.562.902L39.64 24.9a1.041 1.041 0 0 0 0-1.803m-11.12 6.422l-7.998-4.617a1.041 1.041 0 0 0-1.562.901v9.235a1.041 1.041 0 0 0 1.562.902l7.997-4.618a1.041 1.041 0 0 0 0-1.803m.001-12.841l-7.998-4.617a1.041 1.041 0 0 0-1.562.901v9.235a1.041 1.041 0 0 0 1.562.902l7.997-4.618a1.041 1.041 0 0 0 0-1.803m-11.121-6.421L9.401 5.64a1.041 1.041 0 0 0-1.562.901v9.235a1.041 1.041 0 0 0 1.562.902l7.997-4.618a1.041 1.041 0 0 0 0-1.803m0 12.841L9.401 18.48a1.041 1.041 0 0 0-1.562.901v9.235a1.041 1.041 0 0 0 1.562.902l7.997-4.618a1.041 1.041 0 0 0 0-1.803m0 12.843l-7.997-4.617a1.041 1.041 0 0 0-1.562.901v9.235a1.041 1.041 0 0 0 1.562.902l7.997-4.618a1.041 1.041 0 0 0 0-1.803");
}

</style>

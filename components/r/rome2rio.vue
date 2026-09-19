<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zhiyywvmg"/><path class="d64-rybjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rome2rio" /></template>
<style>
.d64-rybjy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.865 26.466c1.342 1.558 2.827 3.17 4.357 4.898c5.38-6.075 10.209-10.677 10.209-16.656h0C34.43 9.07 29.86 4.5 24.222 4.5S14.014 9.07 14.014 14.708h0v.744c.133 1.8.704 3.486 1.588 5.139");
}

.zhiyywvmg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.115 18.14a10.16 10.16 0 0 0-5.337-1.504c-5.638 0-10.209 4.57-10.209 10.208h0v.744c.414 5.593 5.056 10.091 10.209 15.912c5.38-6.075 10.208-10.677 10.208-16.656h0c0-1.976-.562-3.822-1.534-5.385");
}

</style>

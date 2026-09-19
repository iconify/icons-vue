<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z1hkfti2f"/><circle class="i4qljw5ln"/><circle class="ledjelb8q"/><path class="ens2hobaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:unpopular-music-player" /></template>
<style>
.ens2hobaz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 18.137H31.69m-5.218 0h-8.62m-8.29 0H5.5m37 10.273H28.779m-5.405 0H5.5m37 10.268H17.892m-4.119 0H5.5m37-31.386H24.143m-8.23 0H5.5");
}

.i4qljw5ln {
  cx: 37.313px;
  cy: 12.959px;
  r: 2.054px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ledjelb8q {
  cx: 37.313px;
  cy: 23.044px;
  r: 2.054px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z1hkfti2f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.516 17.647C26.443 6.55 13.461 5.929 11.645 13.91c-.181.797.21.884 1.344.297c2.163-1.119 5.647.25 4.767 4.515c-.7 3.399-7.976 5.737-8.378-2.777c0-13.027 22.996-12.235 22.32 1.763c-.18 17.74-20.359 24.613-21.705 23.509c0 0 16.617-9.296 16.523-23.57");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="su8edmbnr"/><path class="pts6cdc4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:providers-id" /></template>
<style>
.pts6cdc4h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.805 4.362H23.786c-6.49 0-11.75 5.26-11.75 11.75s5.26 11.749 11.75 11.749c2.615 0 5.03-.854 6.982-2.298");
}

.su8edmbnr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.624 25.71a11.7 11.7 0 0 0-1.588 5.902c0 6.49 5.26 11.75 11.75 11.75s11.75-5.261 11.75-11.75s-5.261-11.75-11.75-11.75c-2.524 0-4.862.796-6.777 2.15m16.939.001a11.7 11.7 0 0 0 1.588-5.902c0-3.244-1.316-6.182-3.442-8.308");
}

</style>

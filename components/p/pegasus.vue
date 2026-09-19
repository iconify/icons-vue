<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t3q-fbnmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pegasus" /></template>
<style>
.t3q-fbnmi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.51 22.35L4.5 25.43v5.83l13.01-3.08zm4.15-5.28a3.24 3.24 0 0 1 6.4-.72l15.07-3.44V7.07l-18.32 4.19l-7.3-1.81v3.48l-13 3v5.84l17.25-3.9a3.3 3.3 0 0 1-.1-.8m21.72-.63l-6 1.51c.18 4.35-5.5 11-12.45 12.32L4.5 34.91v5.84l13-3v3.17h7.4v-4.85c10.6-2.26 19.76-11.47 18.48-19.63");
}

</style>

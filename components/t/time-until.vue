<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="psafdqbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:time-until" /></template>
<style>
.psafdqbvc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.6 4.5v2.373l10.092 17.22L11.6 41.356V43.5h24.8v-2.172L26.398 24.093L36.4 6.921V4.5z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="poc2rhbvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:plexamp" /></template>
<style>
.poc2rhbvq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 24h18.944L12.808 9.342h4.075L27.519 24L16.883 38.658h4.074L31.594 24L20.957 9.342h4.075L35.668 24L25.032 38.658h4.075L39.743 24H43.5");
}

</style>

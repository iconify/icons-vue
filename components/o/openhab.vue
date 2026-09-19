<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fr2fuwblq"/><path class="j0xlcibuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:openhab" /></template>
<style>
.fr2fuwblq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.86 38.21a21.44 21.44 0 1 0-4.15-7.08");
}

.j0xlcibuf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 34.96l18.55-18.55l14.07 14.06");
}

</style>

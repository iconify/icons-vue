<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lagch7_7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:privy" /></template>
<style>
.lagch7_7o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.16 32.837l17.67-17.671c4.88-4.88 12.791-4.88 17.671-.002l-17.67 17.671c-4.88 4.88-12.792 4.881-17.672.001s-4.88-12.793 0-17.672s12.792-4.88 17.672 0");
}

</style>

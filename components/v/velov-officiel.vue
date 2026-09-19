<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hn33xspyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:velov-officiel" /></template>
<style>
.hn33xspyq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6 16.473h9.385l5.12 15.758h1.222L27.55 14.31l-5.961-1.937L34.84 6.249L42 19.005l-5.961-1.937l-8.02 24.684H14.213z");
}

</style>

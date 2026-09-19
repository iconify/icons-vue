<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q-m9osx0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:trust-wallet" /></template>
<style>
.q-m9osx0x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 43.5c1.35-.062 8.977-4.15 11.767-8.742s4.268-16.815 4.37-24.879C32.072 9.88 26.853 7.352 24 4.5c-2.855 2.855-8.062 5.38-16.138 5.38c0 8.065 1.68 20.217 4.371 24.878S22.65 43.561 24 43.5");
}

</style>

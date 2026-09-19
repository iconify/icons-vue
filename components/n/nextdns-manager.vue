<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="di4oacfpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nextdns-manager" /></template>
<style>
.di4oacfpg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 43.5c12.48-7.639 16.676-17.483 16.676-31.577C34.974 10.686 31.262 9.772 24 4.5c-7.262 5.272-10.974 6.186-16.676 7.423C7.324 26.017 11.52 35.861 24 43.5m11.877-32.746l-22.72 22.997");
}

</style>

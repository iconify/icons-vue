<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mlz7mrnyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-droplet-fill-round" /></template>
<style>
.mlz7mrnyb {
  fill: currentColor;
  d: path("M7 2h10a5 5 0 0 1 5 5v10a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5m5.581 5.186a1 1 0 0 0-1.162 0a11.5 11.5 0 0 0-1.727 1.6c-1.363 1.558-2.344 3.658-1.48 5.703c.206.489.505.933.881 1.307a4.11 4.11 0 0 0 7.018-2.907c0-1.549-.808-2.966-1.803-4.103a11.5 11.5 0 0 0-1.727-1.6");
}

</style>

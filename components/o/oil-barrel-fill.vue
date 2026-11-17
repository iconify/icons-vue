<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fe1x9rumk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:oil-barrel-fill" /></template>
<style>
.fe1x9rumk {
  fill: currentColor;
  d: path("M3 2h18a1 1 0 0 1 0 2h-1v7h1a1 1 0 0 1 0 2h-1v7h1a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2h1v-7H3a1 1 0 0 1 0-2h1V4H3a1 1 0 0 1 0-2m9.581 5.186a1 1 0 0 0-1.162 0a11.5 11.5 0 0 0-1.727 1.6c-1.363 1.558-2.344 3.658-1.48 5.703c.206.489.505.933.881 1.307a4.11 4.11 0 0 0 7.018-2.907c0-1.549-.808-2.966-1.803-4.103a11.5 11.5 0 0 0-1.727-1.6");
}

</style>

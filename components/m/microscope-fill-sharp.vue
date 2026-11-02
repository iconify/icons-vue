<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-_snqbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:microscope-fill-sharp" /></template>
<style>
.c-_snqbvw {
  fill: currentColor;
  d: path("M8 2h4a1 1 0 0 1 1 1v2a1 1 0 0 1 1 1v3h1c1.596 0 3.117.627 4.243 1.757A5.98 5.98 0 0 1 21 15a6.97 6.97 0 0 1-2.05 4.95l-.002.002l-.049.048H21a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2h11a5 5 0 0 0 5-5a3.97 3.97 0 0 0-1.172-2.828A3.97 3.97 0 0 0 15 11h-1v2a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1V3a1 1 0 0 1 1-1M6 16h8a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2");
}

</style>

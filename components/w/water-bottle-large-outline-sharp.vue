<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ppeagqbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:water-bottle-large-outline-sharp" /></template>
<style>
.ppeagqbhq {
  fill: currentColor;
  d: path("M7 20h10v-2h-2v-7h-2V9h4V7H7v2h2v7h2v2H7zm-2 2v-6h2v-5H5V5h5V4H9V2h6v2h-1v1h5v6h-2v5h2v6zm7-8.5");
}

</style>

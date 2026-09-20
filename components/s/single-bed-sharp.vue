<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2-1_a8ro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:single-bed-sharp" /></template>
<style>
.k2-1_a8ro {
  fill: currentColor;
  d: path("M7 19H6l-.65-2H4v-7h2V5h12v5h2v7h-1.35L18 19h-1l-.65-2h-8.7zm6-9h3V7h-3zm-5 0h3V7H8z");
}

</style>

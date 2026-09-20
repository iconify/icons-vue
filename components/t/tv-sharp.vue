<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ujic83bgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tv-sharp" /></template>
<style>
.ujic83bgb {
  fill: currentColor;
  d: path("M8 21v-2H2V3h20v16h-6v2z");
}

</style>

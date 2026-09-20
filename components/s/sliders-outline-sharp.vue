<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6qjj7bml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sliders-outline-sharp" /></template>
<style>
.v6qjj7bml {
  fill: currentColor;
  d: path("M3 14v-4h18v4zm11-1h6v-2h-6z");
}

</style>

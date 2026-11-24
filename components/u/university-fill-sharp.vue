<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t889zeb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:university-fill-sharp" /></template>
<style>
.t889zeb8x {
  fill: currentColor;
  d: path("M20.351 5.064A1 1 0 0 1 21 6v3a1 1 0 0 1-2 0V7.443l-6.649 2.493a1 1 0 0 1-.702 0l-8-3a1 1 0 0 1 0-1.872l8-3a1 1 0 0 1 .702 0ZM7 12v5a1 1 0 0 1-2 0v-5a1 1 0 0 1 2 0m4 0v5a1 1 0 0 1-2 0v-5a1 1 0 0 1 2 0m4 0v5a1 1 0 0 1-2 0v-5a1 1 0 0 1 2 0m4 0v5a1 1 0 0 1-2 0v-5a1 1 0 0 1 2 0M3 20h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2");
}

</style>

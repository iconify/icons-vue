<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4qvdaclo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-size-decrease-fill-round" /></template>
<style>
.z4qvdaclo {
  fill: currentColor;
  d: path("M3 4h10a1 1 0 0 1 0 2H9v13a1 1 0 0 1-2 0V6H3a1 1 0 0 1 0-2m12 7h6a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2");
}

</style>

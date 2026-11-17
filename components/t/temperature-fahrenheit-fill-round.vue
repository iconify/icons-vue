<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ri6nydjao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:temperature-fahrenheit-fill-round" /></template>
<style>
.ri6nydjao {
  fill: currentColor;
  d: path("M2 7a3 3 0 1 1 6 0a3 3 0 0 1-6 0m19-1h-5a2 2 0 0 0-2 2v3h5a1 1 0 0 1 0 2h-5v6a1 1 0 0 1-2 0V8a4 4 0 0 1 4-4h5a1 1 0 0 1 0 2M4 7a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>

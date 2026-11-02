<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afz3-nqqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shirt-fill-sharp" /></template>
<style>
.afz3-nqqw {
  fill: currentColor;
  d: path("m15.316 3.051l6 2A1 1 0 0 1 22 6v5a1 1 0 0 1-1 1h-2v8a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-8H3a1 1 0 0 1-1-1V6a1 1 0 0 1 .684-.949l6-2A1.002 1.002 0 0 1 10 4a2 2 0 1 0 4 0a1 1 0 0 1 1.316-.949");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4iuncb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-plus-fill-sharp" /></template>
<style>
.k4iuncb3c {
  fill: currentColor;
  d: path("M2 6V3a1 1 0 0 1 1-1h3a1 1 0 0 1 0 2H4v2a1 1 0 0 1-2 0m8-4h4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2m8 0h3a1 1 0 0 1 1 1v3a1 1 0 0 1-2 0V4h-2a1 1 0 0 1 0-2m-5 6v3h3a1 1 0 0 1 0 2h-3v3a1 1 0 0 1-2 0v-3H8a1 1 0 0 1 0-2h3V8a1 1 0 0 1 2 0M2 14v-4a1 1 0 0 1 2 0v4a1 1 0 0 1-2 0m20 0a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0ZM6 22H3a1 1 0 0 1-1-1v-3a1 1 0 0 1 2 0v2h2a1 1 0 0 1 0 2m16-4v3a1 1 0 0 1-1 1h-3a1 1 0 0 1 0-2h2v-2a1 1 0 0 1 2 0m-12 4a1 1 0 0 1 0-2h4a1 1 0 0 1 0 2Z");
}

</style>

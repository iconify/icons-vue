<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whjv73bhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tram-fill" /></template>
<style>
.whjv73bhl {
  fill: currentColor;
  d: path("M15 2a1 1 0 0 1 0 2h-2v2h4a3 3 0 0 1 3 3v8a3 3 0 0 1-2.411 2.942l.305.611a1 1 0 1 1-1.788.894L15.382 20H8.618l-.724 1.447a1 1 0 1 1-1.788-.894l.305-.611A3 3 0 0 1 4 17V9a3 3 0 0 1 3-3h4V4H9a1 1 0 0 1 0-2ZM7 8a1 1 0 0 0-1 1v3h12V9a1 1 0 0 0-1-1Zm2.01 7H9a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M15 15a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Z");
}

</style>

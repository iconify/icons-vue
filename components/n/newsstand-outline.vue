<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d93vzwbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:newsstand-outline" /></template>
<style>
.d93vzwbyu {
  fill: currentColor;
  d: path("M2 20v-2h20v2zm2-4V8h2v8zm4 0V4h2v12zm4 0V4h2v12zm7 0l-4-7l1.75-1l4 7z");
}

</style>

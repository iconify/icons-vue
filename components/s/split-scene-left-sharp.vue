<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-q_-0bar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:split-scene-left-sharp" /></template>
<style>
.d-q_-0bar {
  fill: currentColor;
  d: path("M15 20V4h6v16zm-4 2v-2H3V4h8V2h2v20z");
}

</style>

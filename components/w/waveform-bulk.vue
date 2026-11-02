<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9bdq4btr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:waveform-bulk" /></template>
<style>
.h9bdq4btr {
  fill: currentColor;
  d: path("M13 21a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm-4-3a1 1 0 0 1-2 0V6a1 1 0 0 1 2 0Zm8-1a1 1 0 0 1-2 0V7a1 1 0 0 1 2 0ZM5 14a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0Zm16 0a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0Z");
}

</style>

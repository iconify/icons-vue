<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thf00h5wg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:touchpad-fill" /></template>
<style>
.thf00h5wg {
  fill: currentColor;
  d: path("M5 4h14a3 3 0 0 1 3 3v6H2V7a3 3 0 0 1 3-3m6 16H5a3 3 0 0 1-3-3v-2h9Zm11-5v2a3 3 0 0 1-3 3h-6v-5Z");
}

</style>

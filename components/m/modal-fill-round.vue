<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uej_ibcbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:modal-fill-round" /></template>
<style>
.uej_ibcbi {
  fill: currentColor;
  d: path("M2 8a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 21H7a5 5 0 0 1-5-5Zm2 8a3 3 0 0 0 3 3h10a3 3 0 0 0 3-3V8a3 3 0 0 0-3-3H7a3 3 0 0 0-3 3Zm5-9h6a3 3 0 0 1 3 3v4a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3v-4a3 3 0 0 1 3-3");
}

</style>

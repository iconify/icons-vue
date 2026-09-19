<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcwe87b8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-settings-cell" /></template>
<style>
.pcwe87b8j {
  fill: currentColor;
  d: path("M7 24h2v-2H7zm4 0h2v-2h-2zm4 0h2v-2h-2zM6 0v20h12V0zm10 16H8V4h8z");
}

</style>

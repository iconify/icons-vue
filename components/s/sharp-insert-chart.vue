<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igydykg9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-insert-chart" /></template>
<style>
.igydykg9y {
  fill: currentColor;
  d: path("M21 3H3v18h18zM9 17H7v-7h2zm4 0h-2V7h2zm4 0h-2v-4h2z");
}

</style>

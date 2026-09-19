<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmr8znbzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-looks-4" /></template>
<style>
.nmr8znbzw {
  fill: currentColor;
  d: path("M21.04 3h-18v18h18zm-6 14h-2v-4h-4V7h2v4h2V7h2z");
}

</style>

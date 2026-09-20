<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7exfsbns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:web-traffic" /></template>
<style>
.l7exfsbns {
  fill: currentColor;
  d: path("M2 12v-2h3v2zm3.4 5.55L4 16.1L6.1 14l1.45 1.4zM6.1 8L4 5.9l1.4-1.45L7.55 6.6zM18 20l-4.75-4.75L12 19L9 9l10 3l-3.7 1.3L20 18zM10 6V3h2v3zm5.9 2l-1.45-1.4l2.15-2.15l1.4 1.4z");
}

</style>

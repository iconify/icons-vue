<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="geb8bccta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:musical-note" /></template>
<style>
.geb8bccta {
  fill: var(--svg-color--4d5357, #4d5357);
  d: path("M25.4 2v36.7c-1.2-.4-3.7-.6-5.2-.6c-13.6 0-13.6 16.6 0 16.6c5.9 0 11.7-3.7 11.7-8.3V25.8L47.4 31v15c-1.2-.4-3.7-.6-5.2-.6c-13.6 0-13.6 16.6 0 16.6c5.9 0 11.7-3.7 11.7-8.3V11.4zm22 21.5l-15.5-5.3v-6.3l15.5 5.4z");
}

</style>

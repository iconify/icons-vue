<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udmduuuhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:terminal-add-sharp" /></template>
<style>
.udmduuuhk {
  fill: currentColor;
  d: path("m7.5 16.289l-.689-.689L9.388 13l-2.6-2.6l.713-.688L10.789 13zm5 .211v-1h5v1zM3 19V5h9.633q-.012.13-.015.253q-.002.124-.002.266q0 .67.135 1.289T13.166 8H4v9.385q0 .23.192.423t.423.192h14.77q.23 0 .423-.192t.192-.423v-6.21q.28-.061.521-.15q.24-.089.479-.21V19zM18 9V6h-3V5h3V2h1v3h3v1h-3v3z");
}

</style>

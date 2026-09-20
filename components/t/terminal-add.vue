<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyiv3-bgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:terminal-add" /></template>
<style>
.wyiv3-bgd {
  fill: currentColor;
  d: path("m7.5 16.289l-.689-.689L9.388 13l-2.6-2.6l.713-.688L10.789 13zm5 .211v-1h5v1zM4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h8.018q-.012.135-.015.257t-.002.262q0 .672.135 1.29T13.166 8H4v9.385q0 .23.192.423t.423.192h14.77q.23 0 .423-.192t.192-.423v-6.21q.28-.061.521-.15q.24-.089.479-.21v6.57q0 .69-.462 1.152T19.385 19zM18 9V6h-3V5h3V2h1v3h3v1h-3v3z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ry7lgfbcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sticker-fill" /></template>
<style>
.ry7lgfbcx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M23 12C23 5.9249 18.0751 1 12 1C5.9249 1 1 5.9249 1 12C1 18.0751 5.9249 23 12 23C12.2652 23 12.5196 22.8946 12.7071 22.7071L22.7071 12.7071C22.8946 12.5196 23 12.2652 23 12ZM19.8284 12.7574L12.7574 19.8284C12.8516 15.9629 15.9629 12.8516 19.8284 12.7574Z");
}

</style>

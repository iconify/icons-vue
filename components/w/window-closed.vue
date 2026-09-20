<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fegfyzu5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:window-closed" /></template>
<style>
.fegfyzu5g {
  fill: currentColor;
  d: path("M4 21V3h16v18zm3-10h4v-1h2v1h4V6H7zm0 7h10v-5H7zm-1 1h12V5H6z");
}

</style>

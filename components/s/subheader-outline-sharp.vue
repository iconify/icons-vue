<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fm16020hs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:subheader-outline-sharp" /></template>
<style>
.fm16020hs {
  fill: currentColor;
  d: path("M6.616 9.192h8v-2h-8zM4 20V4h16v16zm1-1h14V5H5zm0 0V5z");
}

</style>

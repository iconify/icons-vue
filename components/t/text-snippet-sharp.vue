<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qk-mwpqsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:text-snippet-sharp" /></template>
<style>
.qk-mwpqsh {
  fill: currentColor;
  d: path("M3 21V3h12l6 6v12zm4-4h10v-2H7zm0-4h10v-2H7zm0-4h7V7H7z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2x452giv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:move-selection-up-sharp" /></template>
<style>
.a2x452giv {
  fill: currentColor;
  d: path("M6 14V2h12v12zm10 4v-2h2v2zM6 18v-2h2v2zm10 4v-2h2v2zm-5 0v-2h2v2zm-5 0v-2h2v2z");
}

</style>

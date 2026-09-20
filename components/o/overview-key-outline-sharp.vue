<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edw4rna9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:overview-key-outline-sharp" /></template>
<style>
.edw4rna9l {
  fill: currentColor;
  d: path("M1 19V5h14v14zm2-2h10V7H3zm14 2V5h2v14zm4 0V5h2v14zM3 17V7z");
}

</style>

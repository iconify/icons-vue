<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4qmotbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:present-to-all-sharp" /></template>
<style>
.c4qmotbik {
  fill: currentColor;
  d: path("M11.5 15.308h1v-4.689l2.1 2.095l.713-.714L12 8.692L8.692 12l.714.708l2.094-2.094zM3 19V5h18v14z");
}

</style>

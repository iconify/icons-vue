<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atd6xe2uu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:molecule-24-filled" /></template>
<style>
.atd6xe2uu {
  fill: currentColor;
  d: path("M16 12a5 5 0 1 0-4.337-2.51l-2.714 1.808a4 4 0 1 0 .23 5.13l3.887 1.943a3 3 0 1 0 .672-1.341L9.85 15.087a4 4 0 0 0-.113-2.513l2.863-1.907A4.98 4.98 0 0 0 16 12");
}

</style>

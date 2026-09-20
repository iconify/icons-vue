<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4rimwigs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:subdirectory-arrow-left" /></template>
<style>
.p4rimwigs {
  fill: currentColor;
  d: path("m10 20l-5-5l5.006-5.006l.707.714L6.922 14.5H17V5h1v10.5H6.921l3.793 3.787z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egb2mw23k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:markdown-document-outline-sharp" /></template>
<style>
.egb2mw23k {
  fill: currentColor;
  d: path("M3.98 20V4H20v7.5h-1V5H4.98v14h5.712v1zm6.712-3.75v-1H7.731v1zm0-3.75v-1H7.731v1zm2.385 8.5v-7.115H21V21h-1v-5.692q0-.174-.134-.299q-.135-.125-.308-.125h-2.02v4.25h-1v-4.25H14.5q-.173 0-.298.126t-.125.298V21zm-8.096-9.5V19V5z");
}

</style>

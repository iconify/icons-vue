<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGvpO3udzK)" class="nq7xvtb3e"/><defs><linearGradient id="SVGvpO3udzK" x1="3" x2="21" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop class="yzcjzeb6o"/><stop offset="1" class="k4mpqtbvz"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mkr" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k4mpqtbvz {
  stop-color: var(--svg-color--586979, #586979);
}

.nq7xvtb3e {
  d: path("M3.224 6.66a.45.45 0 0 1 .448-.001l7.199 4.095a.45.45 0 0 1 .228.39v5.806a.45.45 0 1 1-.9 0v-5.544L3.9 7.824v9.126a.45.45 0 0 1-.9 0v-9.9a.45.45 0 0 1 .224-.39m17.552 0a.45.45 0 0 0-.449-.001l-7.198 4.095a.45.45 0 0 0-.228.39v5.806a.45.45 0 0 0 .9 0v-5.544L20.1 7.824v9.126a.45.45 0 0 0 .9 0v-9.9a.45.45 0 0 0-.224-.39");
}

.yzcjzeb6o {
  stop-color: var(--svg-color--1bc4a3, #1bc4a3);
}

</style>

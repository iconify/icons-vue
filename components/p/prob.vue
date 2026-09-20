<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="oyo4cy7cy"><path class="f57pikb3v"/><path class="wvnufyb7d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:prob" /></template>
<style>
.f57pikb3v {
  d: path("m13.89 8.225l-1.5-.85c-.25-.14-.655-.14-.9 0l-1.505.85c-.325.184-.325.484 0 .67l1.5.864c.25.14.65.14.9 0l1.5-.865c.325-.185.325-.485 0-.67z");
}

.oyo4cy7cy {
  fill: var(--svg-color--4231c8, #4231c8);
}

.wvnufyb7d {
  d: path("m19.55 7.17l-7.105-4.064a.99.99 0 0 0-.89 0L4.445 7.17c-.25.14-.445.485-.445.765v8.13c0 .28.2.625.445.765l7.11 4.065c.25.14.645.14.89 0l7.11-4.065c.25-.14.445-.485.445-.765v-8.13c0-.28-.2-.625-.445-.765zm-3.165 1.89l-4.05 2.365a.94.94 0 0 1-.88 0L9.045 9.85c-.32-.185-.55-.035-.55.33v4.535c0 .36-.295.52-.615.35l-.435-.23a.94.94 0 0 1-.45-.75V9.15c0-.28.19-.62.435-.76l4.025-2.34a.98.98 0 0 1 .885 0l4.045 2.34c.32.18.32.485 0 .67");
}

</style>

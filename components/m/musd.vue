<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="yi9s_8byc"><path class="mcssb3bhl"/><path class="m27hp7j2k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:musd" /></template>
<style>
.m27hp7j2k {
  d: path("M13.4 7.5h3.077s.034-.186.023-.467c-.045-.922-.45-2.908-4.585-2.908c-4.578 0-4.668 2.762-4.668 3.173c0 .32-.186 2.356 2.508 3.037c2.7.68 3.932.748 3.932 1.744c0 1.001-.872 1.293-1.597 1.293c-.732 0-1.778-.073-1.778-1.372H6.937s-.236 3.375 4.978 3.375c5.215 0 5.147-3.15 5.147-3.628c0-.45-.1-2.21-3.06-2.942c-2.953-.731-3.69-.742-3.69-1.772c0-.844 1.17-.94 1.744-.94c.41 0 1.344-.005 1.344 1.407");
}

.mcssb3bhl {
  d: path("M3.563 17.625h16.875V21H3.563zM10.875 3h1.688v12.938h-1.688z");
}

.yi9s_8byc {
  fill: var(--svg-color--f0f3fa, #f0f3fa);
}

</style>

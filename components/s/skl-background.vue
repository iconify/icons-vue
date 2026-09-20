<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mumfproca"/><path class="dwzy1cc1m"/><path class="btydcdk7g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:skl-background" /></template>
<style>
.btydcdk7g {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.5 4.5v2H4v-2zm.5 13v2H4v-2zm-.5-10c2 0 3.25 1.5 3.25 2.5H18c0-.25-.565-1-1.5-1c-1.125 0-1.5.5-1.5 1s.25.75 1.5 1c1.155.23 3.5.75 3.5 2.75c0 1.6-1.75 2.75-3.5 2.75c-1.4 0-3.5-.75-3.5-3h1.5c0 .75 1 1.5 2 1.5c.6 0 1.75-.25 1.75-1.25S17.1 12.6 16.5 12.5c-1.5-.25-3.25-.75-3.25-2.5c0-1.25 1.25-2.5 3.25-2.5");
}

.dwzy1cc1m {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 5h2v14H4z");
}

.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

</style>

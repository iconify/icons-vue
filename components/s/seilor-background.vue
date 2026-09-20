<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mumfproca"/><path clip-rule="evenodd" class="g37y1truv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:seilor-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g37y1truv {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M16 8c0-2.18-1.82-4-4-4S8 5.82 8 8V4C5.82 4 4 5.82 4 8h4c-2.18 0-4 1.82-4 4s1.82 4 4 4H4c0 2.18 1.82 4 4 4v-4c0 2.18 1.82 4 4 4s4-1.82 4-4v4c2.18 0 4-1.82 4-4h-4c2.18 0 4-1.82 4-4s-1.82-4-4-4m0 4v4h-4a4 4 0 0 0 4-4m-8 0a4 4 0 0 1 4-4H8zm0 0a4 4 0 0 0 4 4H8zm8 0V4c2.18 0 4 1.82 4 4h-8a4 4 0 0 1 4 4");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

</style>

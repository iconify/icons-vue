<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="jkazv9b8k"/><path class="gkd-s96ca"/><path class="k7imll63p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:unocss" /></template>
<style>
.gkd-s96ca {
  fill: var(--svg-color--ccc, #ccc);
  d: path("M137.176 59.412C137.176 26.6 163.776 0 196.588 0S256 26.6 256 59.412v53.471c0 3.28-2.66 5.941-5.941 5.941H143.117a5.94 5.94 0 0 1-5.941-5.94z");
}

.jkazv9b8k {
  fill: var(--svg-color--858585, #858585);
  d: path("M137.176 195.927c0-32.813 26.6-59.412 59.412-59.412S256 163.114 256 195.927c0 32.812-26.6 59.412-59.412 59.412s-59.412-26.6-59.412-59.412");
}

.k7imll63p {
  fill: var(--svg-color--4d4d4d, #4d4d4d);
  d: path("M118.824 195.927c0 32.812-26.6 59.412-59.412 59.412S0 228.74 0 195.927v-53.47a5.94 5.94 0 0 1 5.941-5.942h106.942a5.94 5.94 0 0 1 5.941 5.941z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jg7bxtp2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:print-preview" /></template>
<style>
.jg7bxtp2r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.25 6.25h.25q2.75 0 2.75 2.75v3.5q0 1.047-.399 1.695Q16.453 14 17.25 14q3.25 0 3.25 3.25q0 1.095-.369 1.821l1.399 1.399q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-1.399-1.399q-.726.369-1.821.369q-3.25 0-3.25-3.25q0-1.339.551-2.126q-.462.126-1.051.126h-.25v2.5q0 1.036-.732 1.768t-1.768.732h-3.5q-2.5 0-2.5-2.5v-2.5H4.5q-2.75 0-2.75-2.75V9q0-1.139.805-1.945q.806-.805 1.945-.805h.25V4.5q0-1.75 1.75-1.75h5q1.75 0 1.75 1.75zm-7 0V4.5q0-.25.25-.25h5q.25 0 .25.25v1.75z");
}

</style>

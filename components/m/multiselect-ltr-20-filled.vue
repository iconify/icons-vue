<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z9x4k-bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:multiselect-ltr-20-filled" /></template>
<style>
.z9x4k-bbl {
  fill: currentColor;
  d: path("M6.252 3.193a.75.75 0 0 1 .055 1.059l-2.25 2.5a.75.75 0 0 1-1.087.028L1.72 5.53a.75.75 0 0 1 1.06-1.06l.691.69l1.722-1.912a.75.75 0 0 1 1.059-.055M8 5.25a.75.75 0 0 1 .75-.75h8.5a.75.75 0 0 1 0 1.5h-8.5A.75.75 0 0 1 8 5.25m0 5a.75.75 0 0 1 .75-.75h8.5a.75.75 0 0 1 0 1.5h-8.5a.75.75 0 0 1-.75-.75m.75 4.25a.75.75 0 0 0 0 1.5h8.5a.75.75 0 0 0 0-1.5zm-2.443-.248a.75.75 0 1 0-1.114-1.004L3.47 15.161l-.69-.691a.75.75 0 0 0-1.061 1.06l1.25 1.25a.75.75 0 0 0 1.087-.028z");
}

</style>

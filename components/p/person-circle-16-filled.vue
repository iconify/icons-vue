<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kxq_mzfbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-circle-16-filled" /></template>
<style>
.kxq_mzfbn {
  fill: currentColor;
  d: path("M8 1a7 7 0 1 1 0 14A7 7 0 0 1 8 1M6 8.5A1.5 1.5 0 0 0 4.5 10c0 1.25 1 2.5 3.5 2.5s3.5-1.255 3.5-2.5A1.5 1.5 0 0 0 10 8.5zm2-5a2 2 0 1 0 0 4a2 2 0 0 0 0-4");
}

</style>

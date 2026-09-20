<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s3scr0bqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-insert-row-20-filled" /></template>
<style>
.s3scr0bqb {
  fill: currentColor;
  d: path("M3.5 16a.5.5 0 0 0 0 1h13a.5.5 0 0 0 0-1zm0-13a.5.5 0 0 0 0 1h13a.5.5 0 0 0 0-1zM3 11a2 2 0 0 0 2 2h2V7H5a2 2 0 0 0-2 2zm9 2H8V7h4zm1 0V7h2a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2z");
}

</style>

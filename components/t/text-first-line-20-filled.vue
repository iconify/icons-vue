<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rljokabaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-first-line-20-filled" /></template>
<style>
.rljokabaf {
  fill: currentColor;
  d: path("M4.28 2.22a.75.75 0 0 0-1.06 1.06l.97.97l-.97.97a.75.75 0 0 0 1.06 1.06l1.5-1.5a.75.75 0 0 0 0-1.06zM16.25 3.5h-7.5a.75.75 0 0 0 0 1.5h7.5a.75.75 0 0 0 0-1.5m-12.5 10a.75.75 0 0 0 0 1.5h12.5a.75.75 0 0 0 0-1.5zm12.5-3.5H3.75a.75.75 0 0 1 0-1.5h12.5a.75.75 0 0 1 0 1.5");
}

</style>

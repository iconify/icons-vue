<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vw6w5fb-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:next-16-filled" /></template>
<style>
.vw6w5fb-e {
  fill: currentColor;
  d: path("M2 3.002a1 1 0 0 1 1.578-.816l7 4.963a1 1 0 0 1 .007 1.628l-7 5.037A1 1 0 0 1 2 13.003zM14 2.5a.5.5 0 1 0-1 0v11a.5.5 0 0 0 1 0z");
}

</style>

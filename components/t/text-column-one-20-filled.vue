<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="prt2dfblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-column-one-20-filled" /></template>
<style>
.prt2dfblb {
  fill: currentColor;
  d: path("M15 5.75a.75.75 0 0 0-.75-.75h-8.5a.75.75 0 0 0 0 1.5h8.5a.75.75 0 0 0 .75-.75m0 3a.75.75 0 0 0-.75-.75h-8.5a.75.75 0 0 0 0 1.5h8.5a.75.75 0 0 0 .75-.75m0 3a.75.75 0 0 0-.75-.75h-8.5a.75.75 0 0 0 0 1.5h8.5a.75.75 0 0 0 .75-.75m0 3a.75.75 0 0 0-.75-.75h-8.5a.75.75 0 0 0 0 1.5h8.5a.75.75 0 0 0 .75-.75");
}

</style>

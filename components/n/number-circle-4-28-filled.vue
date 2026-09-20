<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="jqf2pfbmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:number-circle-4-28-filled" /></template>
<style>
.jqf2pfbmx {
  fill: currentColor;
  d: path("M2 14C2 7.373 7.373 2 14 2s12 5.373 12 12s-5.373 12-12 12S2 20.627 2 14m14.5-5.581c0-1.092-1.42-1.517-2.02-.605l-5.403 8.214a.95.95 0 0 0 .794 1.472h5.128v1.75a.75.75 0 0 0 1.5 0V17.5H17.5a.75.75 0 0 0 0-1.5h-1zM15 9.755V16h-4.11z");
}

</style>

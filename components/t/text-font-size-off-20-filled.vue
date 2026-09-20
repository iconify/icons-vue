<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iupajfnlo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-font-size-off-20-filled" /></template>
<style>
.iupajfnlo {
  fill: currentColor;
  d: path("M2.146 2.146a.5.5 0 0 1 .707 0l15 15a.5.5 0 0 1-.707.707L11.793 12.5h-1.208l-1.381 3.759a.75.75 0 0 1-1.404.011L6.921 14H4.255l-.798 2.25a.75.75 0 1 1-1.414-.501l2.75-7.75a.75.75 0 0 1 1.407-.02l2.282 5.896l1.258-3.428l-7.594-7.594a.5.5 0 0 1 0-.707M13.007 3a.75.75 0 0 1 .702.504l4.25 12.25a1 1 0 0 1 .028.111L15.57 13.45l-.33-.95h-.62l-1.5-1.5h1.6l-1.74-5.02l-1.31 3.568l-1.17-1.17l1.796-4.887A.75.75 0 0 1 13.007 3m-8.22 9.5h1.554l-.81-2.094z");
}

</style>

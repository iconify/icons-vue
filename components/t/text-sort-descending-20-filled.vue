<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d708o75lm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-sort-descending-20-filled" /></template>
<style>
.d708o75lm {
  fill: currentColor;
  d: path("M4 2a.75.75 0 1 0 0 1.5h2.527L3.394 7.809A.75.75 0 0 0 4 9h4a.75.75 0 0 0 0-1.5H5.473l3.134-4.309A.75.75 0 0 0 8 2zm2.709 8.505a.75.75 0 0 0-1.418 0l-2.25 6.5a.75.75 0 1 0 1.418.49l.344-.995h2.394l.344.995a.75.75 0 1 0 1.418-.49zM6 13.043L6.678 15H5.323zM14.25 2a.75.75 0 0 1 .75.75v12.572l1.447-1.579a.75.75 0 0 1 1.106 1.014l-2.75 3a.75.75 0 0 1-1.106 0l-2.75-3a.75.75 0 0 1 1.106-1.014l1.447 1.579V2.75a.75.75 0 0 1 .75-.75");
}

</style>

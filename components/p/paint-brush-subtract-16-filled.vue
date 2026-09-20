<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ouzxfsbkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:paint-brush-subtract-16-filled" /></template>
<style>
.ouzxfsbkq {
  fill: currentColor;
  d: path("M9 1v3.5a.5.5 0 0 0 1 0V1h1.5a.5.5 0 0 1 .5.5v4.522A5.48 5.48 0 0 0 8.337 7H2V1.5a.5.5 0 0 1 .5-.5H7v2.5a.5.5 0 0 0 1 0V1zM6 11.5c0-1.33.472-2.55 1.257-3.5H2v1a2 2 0 0 0 2 2h1v2a2 2 0 0 0 1.997 2h.006q.123 0 .242-.015A5.48 5.48 0 0 1 6 11.5m5.5 4.5a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9M9 11.5a.5.5 0 0 1 .5-.5h4a.5.5 0 0 1 0 1h-4a.5.5 0 0 1-.5-.5");
}

</style>

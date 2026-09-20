<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fy00m8bqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:panel-left-text-dismiss-16-filled" /></template>
<style>
.fy00m8bqs {
  fill: currentColor;
  d: path("M2 5.5A2.5 2.5 0 0 1 4.5 3h7A2.5 2.5 0 0 1 14 5.5v1.1a5.5 5.5 0 0 0-1-.393V5.5A1.5 1.5 0 0 0 11.5 4H8v3.257A5.49 5.49 0 0 0 6 11.5a5.5 5.5 0 0 0 .207 1.5H4.5A2.5 2.5 0 0 1 2 10.5zM4.5 5a.5.5 0 0 0 0 1h1a.5.5 0 0 0 0-1zM4 8a.5.5 0 0 0 .5.5h1a.5.5 0 0 0 0-1h-1A.5.5 0 0 0 4 8m.5 2a.5.5 0 0 0 0 1h1a.5.5 0 0 0 0-1zM16 11.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-3.793 0l1.147-1.146a.5.5 0 0 0-.708-.708L11.5 10.793l-1.146-1.147a.5.5 0 0 0-.708.708l1.147 1.146l-1.147 1.146a.5.5 0 0 0 .708.708l1.146-1.147l1.146 1.147a.5.5 0 0 0 .708-.708z");
}

</style>

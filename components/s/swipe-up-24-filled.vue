<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jb_5pfbnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:swipe-up-24-filled" /></template>
<style>
.jb_5pfbnw {
  fill: currentColor;
  d: path("M12 18a1 1 0 0 0 1-1V5.415l1.293 1.292a1 1 0 0 0 1.32.083l.094-.083a1 1 0 0 0 .083-1.32l-.083-.094l-3-3a1 1 0 0 0-1.32-.083l-.094.083l-3 3a1 1 0 0 0 1.32 1.497l.094-.083L11 5.415V17a1 1 0 0 0 1 1m0 4a5 5 0 0 0 2-9.584v1.712a3.5 3.5 0 1 1-4 0v-1.712A5.001 5.001 0 0 0 12 22");
}

</style>

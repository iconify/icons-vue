<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gc-tstb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:music-note-2-20-filled" /></template>
<style>
.gc-tstb5y {
  fill: currentColor;
  d: path("M15.987 3.016a1 1 0 0 0-1.285-.79l-7 2.187A1 1 0 0 0 7 5.368V13.5a2.5 2.5 0 1 0 1 2V8.368l7-2.188v5.32a2.5 2.5 0 1 0 1 2V3.18q0-.083-.013-.164");
}

</style>

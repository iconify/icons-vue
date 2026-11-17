<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srjl5vbnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:remote-control-fill" /></template>
<style>
.srjl5vbnd {
  fill: currentColor;
  d: path("M11 2v2a1 1 0 0 0 2 0V2h2a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3ZM9.236 8.832a3 3 0 1 0 5.527 2.335a3 3 0 0 0-5.527-2.335M10.01 14H10a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M14 14a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm-3.99 3H10a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M14 17a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Z");
}

</style>

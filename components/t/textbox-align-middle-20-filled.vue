<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wfj78cbtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:textbox-align-middle-20-filled" /></template>
<style>
.wfj78cbtw {
  fill: currentColor;
  d: path("M5.5 3A2.5 2.5 0 0 0 3 5.5v9A2.5 2.5 0 0 0 5.5 17h9a2.5 2.5 0 0 0 2.5-2.5v-9A2.5 2.5 0 0 0 14.5 3zm1 5h7a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1m0 3h7a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1");
}

</style>

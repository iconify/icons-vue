<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sxwtf-bxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:midi-off-20-regular" /></template>
<style>
.sxwtf-bxi {
  fill: currentColor;
  d: path("M2.146 2.147a.5.5 0 0 1 .708 0l15 15a.5.5 0 0 1-.707.707L15.293 16H4a2 2 0 0 1-2-2V6a2 2 0 0 1 1.389-1.904L2.146 2.854a.5.5 0 0 1 0-.707M16 4a2 2 0 0 1 2 2v8c0 .521-.201.995-.528 1.35l-.708-.707A1 1 0 0 0 17 14v-4h-2v2.879l-1-1V10h-1.879l-1-1H17V6a1 1 0 0 0-1-1H7.121l-1-1zM3 14a1 1 0 0 0 1 1h10.293L12 12.707v.793a.5.5 0 1 1-1 0v-1.793L9.293 10H9v3.5a.5.5 0 1 1-1 0V10H6v3.5a.5.5 0 1 1-1 0V10H3zm1-9a1 1 0 0 0-1 1v3h5.293l-4-4zm1.25 1.5a.75.75 0 1 1 0 1.5a.75.75 0 0 1 0-1.5M14.5 6a.5.5 0 0 1 0 1h-2a.5.5 0 0 1 0-1z");
}

</style>

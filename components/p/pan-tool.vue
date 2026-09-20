<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkf9r66-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pan-tool" /></template>
<style>
.xkf9r66-b {
  fill: currentColor;
  d: path("M10.916 21.5q-.624 0-1.164-.28t-.908-.808l-6.125-8.98l.216-.209q.32-.321.76-.348t.809.233L8 13.537v-8.48q0-.212.144-.355t.357-.144t.356.144t.143.356V11.5h2.673V3.058q0-.213.144-.356t.357-.144t.356.144t.143.356V11.5h2.673V4.058q0-.213.144-.356q.144-.144.357-.144t.356.144t.143.356V11.5H19v-6q0-.213.144-.356T19.501 5t.356.144T20 5.5V18q0 1.458-1.021 2.479T16.5 21.5z");
}

</style>

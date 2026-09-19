<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbzq51bgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-folder-off" /></template>
<style>
.rbzq51bgb {
  fill: currentColor;
  d: path("m12 6l-2-2H6.83L22 19.17V6zM2.1 2.1L.69 3.51L2 4.83V20h15.17l3.32 3.31l1.41-1.41z");
}

</style>

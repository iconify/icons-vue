<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-ctpsmsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:splitscreen-landscape-add-outline" /></template>
<style>
.e-ctpsmsx {
  fill: currentColor;
  d: path("M13 16h5V8h-5zm-7 0h5V8H6zm13-8V6h-2V4h2V2h2v2h2v2h-2v2zM4 18V6zm18-8v8q0 .825-.587 1.413T20 20H4q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h11v2H4v12h16v-8z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7l-j_bcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:propane-tank-sharp" /></template>
<style>
.f7l-j_bcs {
  fill: currentColor;
  d: path("M5 13.116V9.23q0-1.194.802-2.042t1.967-.93V3h8.462v3.26q1.165.08 1.967.929Q19 8.037 19 9.23v3.885zM8 21q-1.246 0-2.123-.877T5 18v-3.884h14V18q0 1.246-.877 2.123T16 21zm.77-14.77h2.46v-.768h1.54v.769h2.46V4.616q0-.27-.172-.443Q14.885 4 14.616 4H9.385q-.27 0-.443.173t-.173.443z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrsy49b1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:picture-in-picture-small-outline" /></template>
<style>
.zrsy49b1b {
  fill: currentColor;
  d: path("M3 19v-1h16.385q.23 0 .423-.192t.192-.424V5h1v12.385q0 .69-.462 1.153T19.385 19zm6.923-3.384V9.923h7.693v5.693z");
}

</style>

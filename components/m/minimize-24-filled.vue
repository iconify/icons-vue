<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsfmj_w-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:minimize-24-filled" /></template>
<style>
.lsfmj_w-i {
  fill: currentColor;
  d: path("M3.996 13H20a1 1 0 1 0 0-2H3.996a1 1 0 1 0 0 2");
}

</style>

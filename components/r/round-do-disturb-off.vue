<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8kk7hbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-do-disturb-off" /></template>
<style>
.k8kk7hbsv {
  fill: currentColor;
  d: path("M17 11v2h-.88l4.33 4.33A9.9 9.9 0 0 0 22 12c0-5.52-4.48-10-10-10a9.9 9.9 0 0 0-5.33 1.55L14.12 11zm4.17 9.88L3.12 2.83a.996.996 0 1 0-1.41 1.41l2.07 2.07A10 10 0 0 0 2 12c0 5.52 4.48 10 10 10c2.11 0 4.07-.66 5.68-1.78l2.07 2.07c.39.39 1.02.39 1.41 0c.4-.39.4-1.02.01-1.41M7 13v-2h1.46l2 2z");
}

</style>

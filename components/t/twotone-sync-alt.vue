<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vm2d60b4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-sync-alt" /></template>
<style>
.vm2d60b4v {
  fill: currentColor;
  d: path("m18 12l4-4l-4-4v3H3v2h15zM6 12l-4 4l4 4v-3h15v-2H6z");
}

</style>

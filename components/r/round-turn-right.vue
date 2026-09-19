<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cp3k5565o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-turn-right" /></template>
<style>
.cp3k5565o {
  fill: currentColor;
  d: path("M16.29 13.29c.39.39 1.02.39 1.41 0l2.59-2.59a.996.996 0 0 0 0-1.41L17.7 6.7a.996.996 0 1 0-1.41 1.41l.88.89H9c-1.1 0-2 .9-2 2v8c0 .55.45 1 1 1s1-.45 1-1v-8h8.17l-.88.88a.996.996 0 0 0 0 1.41");
}

</style>

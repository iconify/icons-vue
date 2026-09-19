<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8ts1xfpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-east" /></template>
<style>
.h8ts1xfpy {
  fill: currentColor;
  d: path("M14.29 5.71a.996.996 0 0 0 0 1.41L18.17 11H3c-.55 0-1 .45-1 1s.45 1 1 1h15.18l-3.88 3.88a.996.996 0 1 0 1.41 1.41l5.59-5.59a.996.996 0 0 0 0-1.41l-5.6-5.58a.996.996 0 0 0-1.41 0");
}

</style>

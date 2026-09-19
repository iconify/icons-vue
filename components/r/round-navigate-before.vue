<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w088078al"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-navigate-before" /></template>
<style>
.w088078al {
  fill: currentColor;
  d: path("M14.91 6.71a.996.996 0 0 0-1.41 0L8.91 11.3a.996.996 0 0 0 0 1.41l4.59 4.59a.996.996 0 1 0 1.41-1.41L11.03 12l3.88-3.88c.38-.39.38-1.03 0-1.41");
}

</style>

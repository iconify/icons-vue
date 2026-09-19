<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfl048b9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:view-week" /></template>
<style>
.gfl048b9t {
  fill: currentColor;
  d: path("M5.33 20H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2h1.33c1.1 0 2 .9 2 2v12a2 2 0 0 1-2 2M22 18V6c0-1.1-.9-2-2-2h-1.33c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2H20a2 2 0 0 0 2-2m-7.33 0V6c0-1.1-.9-2-2-2h-1.33c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h1.33c1.1 0 2-.9 2-2");
}

</style>

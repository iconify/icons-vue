<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t895g874i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-restaurant" /></template>
<style>
.t895g874i {
  fill: currentColor;
  d: path("M16 6v8h3v8h2V2c-2.76 0-5 2.24-5 4m-5 3H9V2H7v7H5V2H3v7c0 2.21 1.79 4 4 4v9h2v-9c2.21 0 4-1.79 4-4V2h-2z");
}

</style>

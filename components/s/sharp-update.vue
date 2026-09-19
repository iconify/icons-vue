<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9wn0v34n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-update" /></template>
<style>
.u9wn0v34n {
  fill: currentColor;
  d: path("M11 8v5l4.25 2.52l.77-1.28l-3.52-2.09V8zm10 2V3l-2.64 2.64A8.94 8.94 0 0 0 12 3a9 9 0 1 0 9 9h-2c0 3.86-3.14 7-7 7s-7-3.14-7-7s3.14-7 7-7c1.93 0 3.68.79 4.95 2.05L14 10z");
}

</style>

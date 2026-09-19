<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s862hn2gc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-filter-alt" /></template>
<style>
.s862hn2gc {
  fill: currentColor;
  d: path("M4.25 5.61C6.57 8.59 10 13 10 13v5c0 1.1.9 2 2 2s2-.9 2-2v-5s3.43-4.41 5.75-7.39c.51-.66.04-1.61-.8-1.61H5.04c-.83 0-1.3.95-.79 1.61");
}

</style>

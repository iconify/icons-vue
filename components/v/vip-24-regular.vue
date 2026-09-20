<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jwwfsdqwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:vip-24-regular" /></template>
<style>
.jwwfsdqwo {
  fill: currentColor;
  d: path("M18.75 4A3.25 3.25 0 0 1 22 7.25v9.5A3.25 3.25 0 0 1 18.75 20H5.25A3.25 3.25 0 0 1 2 16.75v-9.5A3.25 3.25 0 0 1 5.25 4zM5.25 5.5A1.75 1.75 0 0 0 3.5 7.25v9.5c0 .966.784 1.75 1.75 1.75h13.5a1.75 1.75 0 0 0 1.75-1.75v-9.5a1.75 1.75 0 0 0-1.75-1.75zm3.795 3.494a.75.75 0 0 1 1.41.512L8.54 14.77a1.107 1.107 0 0 1-2.08 0L4.545 9.506a.75.75 0 0 1 1.41-.512l1.545 4.25zM12.25 8.5a.75.75 0 0 1 .75.75v5.5a.75.75 0 0 1-1.5 0v-5.5a.75.75 0 0 1 .75-.75m5 0a2.25 2.25 0 0 1 0 4.5H16v1.75a.75.75 0 0 1-1.5 0v-5.5a.75.75 0 0 1 .75-.75zm-1.25 3h1.25a.75.75 0 0 0 0-1.5H16z");
}

</style>

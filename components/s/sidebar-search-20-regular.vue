<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ljt4g871v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:sidebar-search-20-regular" /></template>
<style>
.ljt4g871v {
  fill: currentColor;
  d: path("M3 5.5A2.5 2.5 0 0 1 5.5 3h9A2.5 2.5 0 0 1 17 5.5v9a2.5 2.5 0 0 1-2.5 2.5h-2.585a1.5 1.5 0 0 0-.354-.56l-.44-.44H14.5a1.5 1.5 0 0 0 1.5-1.5v-9A1.5 1.5 0 0 0 14.5 4h-9A1.5 1.5 0 0 0 4 5.5v2.756a4.5 4.5 0 0 0-1 .502zm5.303 9.096a3.5 3.5 0 1 0-.707.707l2.55 2.55a.5.5 0 0 0 .708-.707zM5.5 15a2.5 2.5 0 1 1 0-5a2.5 2.5 0 0 1 0 5m8-9a.5.5 0 0 0-.5.5v7a.5.5 0 0 0 1 0v-7a.5.5 0 0 0-.5-.5");
}

</style>

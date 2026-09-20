<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jv6vhmvkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:square-dismiss-20-filled" /></template>
<style>
.jv6vhmvkv {
  fill: currentColor;
  d: path("M6 3a3 3 0 0 0-3 3v8a3 3 0 0 0 3 3h3.6A5.5 5.5 0 0 1 17 9.6V6a3 3 0 0 0-3-3zm8.5 16a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9m1.854-6.354a.5.5 0 0 1 0 .708L15.207 14.5l1.147 1.146a.5.5 0 0 1-.708.708L14.5 15.207l-1.146 1.147a.5.5 0 0 1-.708-.708l1.147-1.146l-1.147-1.146a.5.5 0 0 1 .708-.708l1.146 1.147l1.146-1.147a.5.5 0 0 1 .708 0");
}

</style>

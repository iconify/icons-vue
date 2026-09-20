<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hvzsi-bvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slide-text-cursor-20-filled" /></template>
<style>
.hvzsi-bvq {
  fill: currentColor;
  d: path("M2 6.5A2.5 2.5 0 0 1 4.5 4h11A2.5 2.5 0 0 1 18 6.5v6.335l-4.44-4.4A1.5 1.5 0 0 0 11.004 9.5H5.5a.5.5 0 0 0 0 1h5.504L11 16H4.5A2.5 2.5 0 0 1 2 13.5zm3.5.5a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1zm0 5a.5.5 0 0 0 0 1h4a.5.5 0 0 0 0-1zm7.356-2.854a.5.5 0 0 0-.852.354l-.004 8a.5.5 0 0 0 .9.301l1.994-2.647l3.497.776a.5.5 0 0 0 .46-.843z");
}

</style>

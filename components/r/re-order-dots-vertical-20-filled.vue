<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="snt29pbpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:re-order-dots-vertical-20-filled" /></template>
<style>
.snt29pbpn {
  fill: currentColor;
  d: path("M6.5 6a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3m0 5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3M8 14.5a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0M13.5 6a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3M15 9.5a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0M13.5 16a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="scfpd0ibo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:port-usb-a-20-filled" /></template>
<style>
.scfpd0ibo {
  fill: currentColor;
  d: path("M4.5 7A1.5 1.5 0 0 0 3 8.5v3A1.5 1.5 0 0 0 4.5 13h11a1.5 1.5 0 0 0 1.5-1.5v-3A1.5 1.5 0 0 0 15.5 7zm0 1.5h11V10h-11z");
}

</style>

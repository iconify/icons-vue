<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b1_sukbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:port-usb-a-20-regular" /></template>
<style>
.b1_sukbzx {
  fill: currentColor;
  d: path("M4.5 7A1.5 1.5 0 0 0 3 8.5v3A1.5 1.5 0 0 0 4.5 13h11a1.5 1.5 0 0 0 1.5-1.5v-3A1.5 1.5 0 0 0 15.5 7zM4 8.5a.5.5 0 0 1 .5-.5h11a.5.5 0 0 1 .5.5V10H4z");
}

</style>

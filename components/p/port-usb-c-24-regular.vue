<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zklpa5btr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:port-usb-c-24-regular" /></template>
<style>
.zklpa5btr {
  fill: currentColor;
  d: path("M16 10.5a1.5 1.5 0 1 1 0 3H8a1.5 1.5 0 1 1 0-3zM16 9H8a3 3 0 1 0 0 6h8a3 3 0 0 0 0-6");
}

</style>

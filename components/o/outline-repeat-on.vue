<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsoya4wet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-repeat-on" /></template>
<style>
.fsoya4wet {
  fill: currentColor;
  d: path("M21 1H3c-1.1 0-2 .9-2 2v18c0 1.1.9 2 2 2h18c1.1 0 2-.9 2-2V3c0-1.1-.9-2-2-2m-2 18H6.83l1.58 1.58L7 22l-4-4l4-4l1.41 1.42L6.83 17H17v-4h2zm-2-9l-1.41-1.42L17.17 7H7v4H5V5h12.17l-1.58-1.58L17 2l4 4z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-epx7lzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-folder-delete" /></template>
<style>
.b-epx7lzv {
  fill: currentColor;
  d: path("M16.5 10V9h-2v1H12v1.5h1v4c0 .83.67 1.5 1.5 1.5h2c.83 0 1.5-.67 1.5-1.5v-4h1V10zm0 5.5h-2v-4h2zM20 6h-8l-2-2H4c-1.11 0-1.99.89-1.99 2L2 18c0 1.11.89 2 2 2h16c1.11 0 2-.89 2-2V8c0-1.11-.89-2-2-2m0 12H4V6h5.17l2 2H20z");
}

</style>

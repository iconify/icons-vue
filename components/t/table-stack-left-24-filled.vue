<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxnhe2b6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-stack-left-24-filled" /></template>
<style>
.cxnhe2b6h {
  fill: currentColor;
  d: path("M16 21h1.75A3.25 3.25 0 0 0 21 17.75V16h-5zm0-6.5h5v-5h-5zm-1.5-5v5h-5v-5zM16 8h5V6.25A3.25 3.25 0 0 0 17.75 3H16zm-1.5-5v5h-5V3.75a.75.75 0 0 1 .75-.75zm0 13v5h-4.25a.75.75 0 0 1-.75-.75V16zM4.5 3.75a.75.75 0 0 0-1.5 0v16.5a.75.75 0 0 0 1.5 0z");
}

</style>

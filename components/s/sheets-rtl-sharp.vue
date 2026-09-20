<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ym_miyb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sheets-rtl-sharp" /></template>
<style>
.ym_miyb9t {
  fill: currentColor;
  d: path("M4 13V1h16v12zm2-7h5V3H6zm7 0h5V3h-5zm-7 5h5V8H6zm7 0h5V8h-5zM7 22l-4-4l4-4l1.4 1.4L6.825 17H20v2H6.825L8.4 20.6z");
}

</style>

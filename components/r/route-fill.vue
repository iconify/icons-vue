<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubuyvcbzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:route-fill" /></template>
<style>
.ubuyvcbzt {
  fill: currentColor;
  d: path("M15.171 7H8a1 1 0 0 0-1 1v2a.997.997 0 0 0 1 1h8a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H8.829a3 3 0 1 1 0-2H16a1 1 0 0 0 1-1v-2a1 1 0 0 0-1-1H8a3 3 0 0 1-3-3V8a3 3 0 0 1 3-3h7.171a3 3 0 1 1 0 2");
}

</style>

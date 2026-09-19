<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbnyb-bik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-multiple-stop" /></template>
<style>
.nbnyb-bik {
  fill: currentColor;
  d: path("m17 4l4 4l-4 4V9h-4V7h4zM7 17h4v-2H7v-3l-4 4l4 4zm12-2h-2v2h2zm-4 0h-2v2h2zm-4-8H9v2h2zM7 7H5v2h2z");
}

</style>

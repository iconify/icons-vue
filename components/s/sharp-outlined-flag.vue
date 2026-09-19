<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4tcmykbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-outlined-flag" /></template>
<style>
.g4tcmykbx {
  fill: currentColor;
  d: path("m14 6l-1-2H5v17h2v-7h5l1 2h7V6zm4 8h-4l-1-2H7V6h5l1 2h5z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qapqptb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:seat-24-filled" /></template>
<style>
.qapqptb7e {
  fill: currentColor;
  d: path("M3 6.25A3.25 3.25 0 0 1 6.25 3h11.5A3.25 3.25 0 0 1 21 6.25v5.627A4 4 0 0 0 18.5 11a4 4 0 0 0-3.25 1.668A4 4 0 0 0 12 11a4 4 0 0 0-3.25 1.668A4 4 0 0 0 5.5 11c-.946 0-1.815.328-2.5.877zM14.5 15a2.5 2.5 0 0 0-5 0v6h5zm1.5 6h2.75A2.25 2.25 0 0 0 21 18.75V15a2.5 2.5 0 0 0-5 0zm-8 0H5.25A2.25 2.25 0 0 1 3 18.75V15a2.5 2.5 0 0 1 5 0z");
}

</style>

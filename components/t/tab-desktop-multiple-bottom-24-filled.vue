<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9jc2oe5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tab-desktop-multiple-bottom-24-filled" /></template>
<style>
.z9jc2oe5s {
  fill: currentColor;
  d: path("M6.008 5a3.25 3.25 0 0 1 3.24-3h8.002A4.75 4.75 0 0 1 22 6.75v8a3.25 3.25 0 0 1-3 3.24h-.002V9.25A4.25 4.25 0 0 0 14.748 5zM5.25 6A3.25 3.25 0 0 0 2 9.25v7.25h7.25a2.25 2.25 0 0 1 2.25 2.25V22h3.25A3.25 3.25 0 0 0 18 18.75v-9.5A3.25 3.25 0 0 0 14.75 6zM2 18.75V18h7.25a.75.75 0 0 1 .75.75V22H5.25A3.25 3.25 0 0 1 2 18.75");
}

</style>

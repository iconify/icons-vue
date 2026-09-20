<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ifg5nwb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-off-20-filled" /></template>
<style>
.ifg5nwb4l {
  fill: currentColor;
  d: path("M2.854 2.146a.5.5 0 1 0-.708.708l1.48 1.479A3 3 0 0 0 2 7v6a3 3 0 0 0 3 3h5a3 3 0 0 0 2.932-2.361l4.214 4.215a.5.5 0 0 0 .708-.708zM14 11.88l3.076 3.075c.509-.14.922-.598.922-1.207V6.252a1.25 1.25 0 0 0-1.96-1.028L14 6.63zM6.121 4L13 10.879V7a3 3 0 0 0-3-3z");
}

</style>

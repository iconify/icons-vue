<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifrgh_bsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-vertical-align-top" /></template>
<style>
.ifrgh_bsa {
  fill: currentColor;
  d: path("M8 11h3v10h2V11h3l-4-4zM4 3v2h16V3z");
}

</style>

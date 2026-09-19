<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3u-u4_2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-settings-input-component" /></template>
<style>
.d3u-u4_2k {
  fill: currentColor;
  d: path("M5 2c0-.55-.45-1-1-1s-1 .45-1 1v4H1v6h6V6H5zm4 16.82h2V23h2v-4.18h2V14H9zm-8 0h2V23h2v-4.18h2V14H1zM21 6V2c0-.55-.45-1-1-1s-1 .45-1 1v4h-2v6h6V6zm-8-4c0-.55-.45-1-1-1s-1 .45-1 1v4H9v6h6V6h-2zm4 16.82h2V23h2v-4.18h2V14h-6z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4cjb3bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-panorama-horizontal-select" /></template>
<style>
.m4cjb3bko {
  fill: currentColor;
  d: path("M12 5.5c-5.25 0-9.01-1.54-10-1.92V20.4c2.16-.76 5.21-1.9 10-1.9c4.78 0 7.91 1.17 10 1.9V3.6c-2.09.73-5.23 1.9-10 1.9");
}

</style>

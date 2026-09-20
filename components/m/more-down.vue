<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9w6w3bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:more-down" /></template>
<style>
.j9w6w3bqk {
  fill: currentColor;
  d: path("M5.5 18.5V9h1v8.5H15v1zm5-5V4h1v8.5H20v1z");
}

</style>

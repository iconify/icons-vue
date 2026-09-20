<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hohin0bnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:stop-24-regular" /></template>
<style>
.hohin0bnv {
  fill: currentColor;
  d: path("M19.25 4.5a.25.25 0 0 1 .25.25v14.5a.25.25 0 0 1-.25.25H4.75a.25.25 0 0 1-.25-.25V4.75a.25.25 0 0 1 .25-.25zM4.75 3A1.75 1.75 0 0 0 3 4.75v14.5c0 .966.784 1.75 1.75 1.75h14.5A1.75 1.75 0 0 0 21 19.25V4.75A1.75 1.75 0 0 0 19.25 3z");
}

</style>

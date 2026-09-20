<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8j82fe9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stop-outline" /></template>
<style>
.d8j82fe9x {
  fill: currentColor;
  d: path("M8 8v8zm-1 9V7h10v10zm1-1h8V8H8z");
}

</style>

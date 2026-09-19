<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ds85t8b9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-navigate-before" /></template>
<style>
.ds85t8b9e {
  fill: currentColor;
  d: path("M15.61 7.41L14.2 6l-6 6l6 6l1.41-1.41L11.03 12z");
}

</style>

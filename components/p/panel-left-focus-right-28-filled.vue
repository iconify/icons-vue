<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="ttafjm6ja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:panel-left-focus-right-28-filled" /></template>
<style>
.ttafjm6ja {
  fill: currentColor;
  d: path("M2.004 20.25A3.75 3.75 0 0 0 5.754 24H22.25A3.75 3.75 0 0 0 26 20.25V7.75A3.75 3.75 0 0 0 22.25 4H5.755a3.75 3.75 0 0 0-3.75 3.75zm3.75 2.25a2.25 2.25 0 0 1-2.25-2.25V7.75a2.25 2.25 0 0 1 2.25-2.25H9v17z");
}

</style>

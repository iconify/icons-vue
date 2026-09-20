<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j-jvk1b6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:xbox-console-20-filled" /></template>
<style>
.j-jvk1b6z {
  fill: currentColor;
  d: path("M4.5 2a.5.5 0 0 0-.5.5v15a.5.5 0 0 0 .5.5H7V9.5a.5.5 0 0 1 1 0V18h7.5a.5.5 0 0 0 .5-.5v-15a.5.5 0 0 0-.5-.5zm3 4.5a.75.75 0 1 1 0-1.5a.75.75 0 0 1 0 1.5");
}

</style>

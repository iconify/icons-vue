<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="si1naobyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:vault-16-filled" /></template>
<style>
.si1naobyr {
  fill: currentColor;
  d: path("M10 8.5a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1m-9-3A2.5 2.5 0 0 1 3.5 3h9A2.5 2.5 0 0 1 15 5.5v5a2.5 2.5 0 0 1-2.5 2.5h-9A2.5 2.5 0 0 1 1 10.5zm3.5.5a.5.5 0 0 0-.5.5v3a.5.5 0 0 0 1 0v-3a.5.5 0 0 0-.5-.5m6.854 2.647a1.5 1.5 0 0 0 0-1.294l.5-.5a.5.5 0 0 0-.708-.707l-.5.5a1.5 1.5 0 0 0-1.293 0l-.5-.5a.5.5 0 1 0-.707.708l.5.5a1.5 1.5 0 0 0 0 1.293l-.5.5a.5.5 0 1 0 .708.707l.5-.5a1.5 1.5 0 0 0 1.293 0l.5.5a.5.5 0 0 0 .707-.708z");
}

</style>

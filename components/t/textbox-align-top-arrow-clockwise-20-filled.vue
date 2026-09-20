<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qv8j7967n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:textbox-align-top-arrow-clockwise-20-filled" /></template>
<style>
.qv8j7967n {
  fill: currentColor;
  d: path("M14.5 3A2.5 2.5 0 0 1 17 5.5v8.379l-.44-.44a1.5 1.5 0 1 0-2.12 2.121l.439.44h1.414l-1.146-1.146a.5.5 0 1 1 .707-.707l2 2a.5.5 0 0 1 0 .707l-2 2a.5.5 0 1 1-.707-.707L16.293 17H5.5A2.5 2.5 0 0 1 3 14.5v-9A2.5 2.5 0 0 1 5.5 3zm-8 6a.5.5 0 0 0 0 1h7a.5.5 0 0 0 0-1zm0-3a.5.5 0 0 0 0 1h7a.5.5 0 0 0 0-1z");
}

</style>

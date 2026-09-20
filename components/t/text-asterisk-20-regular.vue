<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="doo6irn6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-asterisk-20-regular" /></template>
<style>
.doo6irn6f {
  fill: currentColor;
  d: path("M10.5 2.5a.5.5 0 0 0-1 0v6.293l-4.45-4.45a.5.5 0 1 0-.707.707l4.45 4.45H2.5a.5.5 0 0 0 0 1h6.293l-4.45 4.45a.5.5 0 1 0 .707.707l4.45-4.45V17.5a.5.5 0 0 0 1 0v-6.293l4.45 4.45a.5.5 0 1 0 .707-.707l-4.45-4.45H17.5a.5.5 0 0 0 0-1h-6.293l4.45-4.45a.5.5 0 1 0-.707-.707l-4.45 4.45z");
}

</style>

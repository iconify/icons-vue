<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qf2c3kgra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:more-horizontal-32-filled" /></template>
<style>
.qf2c3kgra {
  fill: currentColor;
  d: path("M7 19a3 3 0 1 0 0-6a3 3 0 0 0 0 6m9 0a3 3 0 1 0 0-6a3 3 0 0 0 0 6m9 0a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

</style>

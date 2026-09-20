<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zixqq3bix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:phone-48-filled" /></template>
<style>
.zixqq3bix {
  fill: currentColor;
  d: path("M16.25 4A4.25 4.25 0 0 0 12 8.25v31.5A4.25 4.25 0 0 0 16.25 44h15.5A4.25 4.25 0 0 0 36 39.75V8.25A4.25 4.25 0 0 0 31.75 4zm5 31.5h5.5a1.25 1.25 0 1 1 0 2.5h-5.5a1.25 1.25 0 1 1 0-2.5");
}

</style>

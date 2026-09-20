<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="xsib-hkdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:shopping-bag-28-filled" /></template>
<style>
.xsib-hkdy {
  fill: currentColor;
  d: path("M8 5.5a3.5 3.5 0 0 1 6-2.45a3.5 3.5 0 0 1 6 2.45V8h2.5A1.5 1.5 0 0 1 24 9.5v13.25A3.25 3.25 0 0 1 20.797 26h-.094a3.25 3.25 0 0 1-3.203-3.25V8h1V5.5a2 2 0 0 0-3.674-1.094A3.5 3.5 0 0 1 15 5.5V8h1v14.75c0 1.257.488 2.4 1.286 3.25H8a4 4 0 0 1-4-4V9.5A1.5 1.5 0 0 1 5.5 8H8zm5.5 0a2 2 0 1 0-4 0V8h4z");
}

</style>

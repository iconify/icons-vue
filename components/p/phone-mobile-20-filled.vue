<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e9quy9biw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:phone-mobile-20-filled" /></template>
<style>
.e9quy9biw {
  d: path("M13.5 2A1.5 1.5 0 0 1 15 3.5v13a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 5 16.5v-13A1.5 1.5 0 0 1 6.5 2zM11 14H9a.5.5 0 0 0 0 1h2a.5.5 0 0 0 0-1z");
  fill: currentColor;
  fill-rule: nonzero;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mns-w4bba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:oval-48-filled" /></template>
<style>
.mns-w4bba {
  fill: currentColor;
  d: path("M4 24c0-8.284 6.716-15 15-15h10c8.284 0 15 6.716 15 15s-6.716 15-15 15H19c-8.284 0-15-6.716-15-15");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="yl41x3qvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:more-circle-28-filled" /></template>
<style>
.yl41x3qvs {
  fill: currentColor;
  d: path("M14 2C7.373 2 2 7.373 2 14s5.373 12 12 12s12-5.373 12-12S20.627 2 14 2M9.5 14a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m6 0a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m6 0a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzzcr1blp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-call-missed-outgoing" /></template>
<style>
.mzzcr1blp {
  fill: currentColor;
  d: path("M19 10.41V15h2V7h-8v2h4.59L12 14.59L4.41 7L3 8.41l9 9z");
}

</style>

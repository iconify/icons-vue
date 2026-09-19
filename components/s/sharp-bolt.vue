<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6naq-7ae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-bolt" /></template>
<style>
.q6naq-7ae {
  fill: currentColor;
  d: path("M11 21h-1l1-7H6.74S10.42 7.54 13 3h1l-1 7h4.28z");
}

</style>

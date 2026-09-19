<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gn9jv4_gz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-format-quote" /></template>
<style>
.gn9jv4_gz {
  fill: currentColor;
  d: path("M5 17h3l2-4V7H4v6h3zm10 0h3l2-4V7h-6v6h3z");
}

</style>

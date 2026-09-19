<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0rqd4bhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-navigate-before" /></template>
<style>
.n0rqd4bhg {
  fill: currentColor;
  d: path("m14.2 6l-6 6l6 6l1.41-1.41L11.03 12l4.58-4.59z");
}

</style>

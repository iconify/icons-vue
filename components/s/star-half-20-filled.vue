<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wsicb_1hq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:star-half-20-filled" /></template>
<style>
.wsicb_1hq {
  fill: currentColor;
  d: path("M10 2.342a.99.99 0 0 0-.896.557l-1.93 3.912l-4.317.627a1 1 0 0 0-.554 1.706l3.124 3.044l-.738 4.3a1 1 0 0 0 1.451 1.054l3.86-2.03z");
}

</style>

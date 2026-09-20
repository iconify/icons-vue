<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="po7f_rbfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-freeze-column-and-row-28-filled" /></template>
<style>
.po7f_rbfj {
  fill: currentColor;
  d: path("M6.75 3A3.75 3.75 0 0 0 3 6.75v14.5A3.75 3.75 0 0 0 6.75 25H17v-6.5h-6v5H6.75a2.25 2.25 0 0 1-2.25-2.25V6.75A2.25 2.25 0 0 1 6.75 4.5h14.5a2.25 2.25 0 0 1 2.25 2.25V11h-5v6H25V6.75A3.75 3.75 0 0 0 21.25 3zm14.5 22H18.5v-6.5H25v2.75A3.75 3.75 0 0 1 21.25 25M17 17v-6h-6v6z");
}

</style>

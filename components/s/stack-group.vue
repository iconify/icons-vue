<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-cauib-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stack-group" /></template>
<style>
.r-cauib-c {
  fill: currentColor;
  d: path("M10.616 21q-.667 0-1.141-.475T9 19.386V15H4.616q-.667 0-1.141-.475T3 13.385v-8.77q0-.666.475-1.14T4.615 3h8.77q.666 0 1.14.475T15 4.615V9h4.385q.666 0 1.14.475t.475 1.14v8.77q0 .666-.475 1.14t-1.14.475z");
}

</style>

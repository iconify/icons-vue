<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9bll4b9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:previous-frame-24-regular" /></template>
<style>
.g9bll4b9h {
  fill: currentColor;
  d: path("M18.5 3.75a.75.75 0 0 1 1.5 0v16.5a.75.75 0 0 1-1.5 0zm-6.239-.44c1.162-.796 2.74.035 2.74 1.443v14.495c0 1.413-1.59 2.244-2.75 1.437L1.753 13.383a1.75 1.75 0 0 1 .01-2.88zm1.24 1.443a.25.25 0 0 0-.392-.206L2.611 11.74a.25.25 0 0 0-.002.412l10.499 7.301a.25.25 0 0 0 .392-.205z");
}

</style>

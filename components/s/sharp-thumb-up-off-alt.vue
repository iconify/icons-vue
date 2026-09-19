<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-_l2mv4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-thumb-up-off-alt" /></template>
<style>
.r-_l2mv4n {
  fill: currentColor;
  d: path("M14.17 1L7 8.18V21h12.31L23 12.4V8h-8.31l1.12-5.38zM1 9h4v12H1z");
}

</style>

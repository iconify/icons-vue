<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="o0m1bxb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:red-triangle-pointed-up" /></template>
<style>
.o0m1bxb5n {
  fill: currentColor;
  d: path("M32 2L2 62h60z");
}

</style>

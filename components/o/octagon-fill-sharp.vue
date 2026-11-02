<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6kccibss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:octagon-fill-sharp" /></template>
<style>
.i6kccibss {
  fill: currentColor;
  d: path("M16 2c.265 0 .52.105.707.293l5 5A1 1 0 0 1 22 8v8c0 .265-.105.52-.293.707l-5 5A1 1 0 0 1 16 22H8a1 1 0 0 1-.707-.293l-5-5A1 1 0 0 1 2 16V8c0-.265.105-.52.293-.707l5-5A1 1 0 0 1 8 2Z");
}

</style>

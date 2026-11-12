<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3__f_40a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tag-minus-fill-sharp" /></template>
<style>
.b3__f_40a {
  fill: currentColor;
  d: path("M15 2c.265 0 .52.105.707.293l4 4A1 1 0 0 1 20 7v14a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V7c0-.265.105-.52.293-.707l4-4A1 1 0 0 1 9 2Zm-2 3h-2a1 1 0 0 0 0 2h2a1 1 0 0 0 0-2m2 9H9a1 1 0 0 0 0 2h6a1 1 0 0 0 0-2");
}

</style>

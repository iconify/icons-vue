<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvp4vn7vv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tag-percent-fill-sharp" /></template>
<style>
.qvp4vn7vv {
  fill: currentColor;
  d: path("M15 2c.265 0 .52.105.707.293l4 4A1 1 0 0 1 20 7v14a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V7c0-.265.105-.52.293-.707l4-4A1 1 0 0 1 9 2Zm-2 3h-2a1 1 0 0 0 0 2h2a1 1 0 0 0 0-2m-5.842 6.221a2 2 0 1 0 3.684 1.558a2 2 0 0 0-3.684-1.558m2.549 7.486l6-6a.999.999 0 1 0-1.414-1.414l-6 6a.999.999 0 1 0 1.414 1.414m6.072 1.135a2 2 0 1 0-1.558-3.684a2 2 0 0 0 1.558 3.684");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5urfnlzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tv-fill" /></template>
<style>
.n5urfnlzt {
  fill: currentColor;
  d: path("M8.707 3.293L12 6.586l3.293-3.293a.999.999 0 1 1 1.414 1.414L14.414 7H19a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3v-8a3 3 0 0 1 3-3h4.586L7.293 4.707a.999.999 0 1 1 1.414-1.414");
}

</style>

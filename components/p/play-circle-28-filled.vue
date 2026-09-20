<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="xn879lj9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:play-circle-28-filled" /></template>
<style>
.xn879lj9z {
  fill: currentColor;
  d: path("M14 2C7.373 2 2 7.373 2 14s5.373 12 12 12s12-5.373 12-12S20.627 2 14 2m-1.234 7.278l6.505 3.862a1 1 0 0 1 0 1.72l-6.505 3.862a1.5 1.5 0 0 1-2.266-1.29v-6.864a1.5 1.5 0 0 1 2.266-1.29");
}

</style>

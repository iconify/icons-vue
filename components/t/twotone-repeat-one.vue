<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8shq4bfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-repeat-one" /></template>
<style>
.s8shq4bfo {
  fill: currentColor;
  d: path("M13 15V9h-1l-2 1v1h1.5v4zm6-2h-2v4H7v-3l-4 4l4 4v-3h12zM17 2v3H5v6h2V7h10v3l4-4z");
}

</style>

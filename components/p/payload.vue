<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":305};
const content = `<path class="wu0mdxd7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:payload" /></template>
<style>
.wu0mdxd7o {
  d: path("M116.204 0L256 84.031v159.5l-105.265 60.896v-159.5L10.772 61.008zM105.49 171.121v124.463L0 232.13z");
}

</style>

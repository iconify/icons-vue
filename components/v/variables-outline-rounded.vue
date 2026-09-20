<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgz28qb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:variables-outline-rounded" /></template>
<style>
.qgz28qb5s {
  fill: currentColor;
  d: path("M4 15.2V8.8q0-.34.232-.57T4.808 8h14.384q.344 0 .576.23T20 8.8v6.4q0 .34-.232.57t-.576.23H4.808q-.343 0-.576-.23T4 15.2m1-.2h14V9H5zm0 0V9z");
}

</style>

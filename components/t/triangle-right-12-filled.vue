<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="vdava9btv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:triangle-right-12-filled" /></template>
<style>
.vdava9btv {
  fill: currentColor;
  d: path("M10.541 6.786a.903.903 0 0 0 0-1.572L3.372 1.122C2.762.774 2 1.211 2 1.91v8.182c0 .698.762 1.135 1.372.787z");
}

</style>

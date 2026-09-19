<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwd3o3boq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-horizontal-distribute" /></template>
<style>
.pwd3o3boq {
  fill: currentColor;
  d: path("M4 22H2V2h2zM22 2h-2v20h2zm-8.5 5h-3v10h3z");
}

</style>

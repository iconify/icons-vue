<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t27c6cbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-sidebar-sharp" /></template>
<style>
.t27c6cbvb {
  fill: currentColor;
  d: path("M18 8V4h4v4zm0 6v-4h4v4zM2 20V4h14v16zm16 0v-4h4v4z");
}

</style>

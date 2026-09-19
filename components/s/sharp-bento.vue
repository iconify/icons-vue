<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ecelpeb9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-bento" /></template>
<style>
.ecelpeb9k {
  fill: currentColor;
  d: path("M16 11V5h6v6zm0 8h6v-6h-6zM14 5v14H2V5zm-4.5 7c0-.83-.67-1.5-1.5-1.5s-1.5.67-1.5 1.5s.67 1.5 1.5 1.5s1.5-.67 1.5-1.5");
}

</style>

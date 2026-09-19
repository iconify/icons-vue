<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjel2mb-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-view-carousel" /></template>
<style>
.rjel2mb-r {
  fill: currentColor;
  d: path("M2 7h4v10H2zm5 12h10V5H7zM9 7h6v10H9zm9 0h4v10h-4z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhef3cc6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-skip-previous" /></template>
<style>
.yhef3cc6i {
  fill: currentColor;
  d: path("M6 6h2v12H6zm3.5 6l8.5 6V6z");
}

</style>

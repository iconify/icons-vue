<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2kl6ibhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:triangle-24-filled" /></template>
<style>
.i2kl6ibhk {
  fill: currentColor;
  d: path("M2.302 16.63c-.86 1.5.222 3.37 1.951 3.37h15.49c1.729 0 2.812-1.87 1.951-3.37L13.95 3.129c-.865-1.507-3.04-1.507-3.904 0z");
}

</style>

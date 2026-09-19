<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2em50b9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-browser-not-supported" /></template>
<style>
.e2em50b9t {
  fill: currentColor;
  d: path("M19 6v10.5l1.95 1.95c.03-.15.05-.3.05-.45V6c0-1.1-.9-2-2-2H6.5l2 2zM3.86 3.95a.9.9 0 0 0-1.27 0a.9.9 0 0 0 0 1.27l.41.42V18c0 1.1.9 2 2 2h12.36l1.42 1.42a.9.9 0 0 0 1.27 0a.9.9 0 0 0 0-1.27zM5 18V7.64L15.36 18z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pv9qmukdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:next-20-filled" /></template>
<style>
.pv9qmukdf {
  fill: currentColor;
  d: path("M3 4.252c0-1 1.116-1.595 1.947-1.038l8.499 5.707a1.25 1.25 0 0 1 .007 2.071l-8.5 5.793A1.25 1.25 0 0 1 3 15.752zM17 3.5a.5.5 0 0 0-1 0v13a.5.5 0 1 0 1 0z");
}

</style>

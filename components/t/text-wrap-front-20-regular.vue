<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pv1ihpcif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-wrap-front-20-regular" /></template>
<style>
.pv1ihpcif {
  fill: currentColor;
  d: path("M3.5 3a.5.5 0 0 0 0 1h13a.5.5 0 0 0 0-1zm3 8h1v2.5a.5.5 0 0 1-1 0zm7 0h-1v2.5a.5.5 0 0 0 1 0zm3-2a.5.5 0 0 1 0 1h-13a.5.5 0 0 1 0-1zM10 5a3.5 3.5 0 0 1 3.465 3H12.45a2.5 2.5 0 0 0-4.9 0H6.535A3.5 3.5 0 0 1 10 5M3.5 15a.5.5 0 0 0 0 1h13a.5.5 0 0 0 0-1z");
}

</style>

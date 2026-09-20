<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t0liimblm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:toggle-multiple-20-filled" /></template>
<style>
.t0liimblm {
  fill: currentColor;
  d: path("M3 5.5A3.5 3.5 0 0 1 6.5 2h7a3.5 3.5 0 1 1 0 7h-7A3.5 3.5 0 0 1 3 5.5m5 0a1.5 1.5 0 1 0-3 0a1.5 1.5 0 0 0 3 0M6.5 11a3.5 3.5 0 1 0 0 7h7a3.5 3.5 0 1 0 0-7zm7 5a1.5 1.5 0 1 1 0-3a1.5 1.5 0 0 1 0 3");
}

</style>

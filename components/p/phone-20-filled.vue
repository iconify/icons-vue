<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d_r2di-zt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:phone-20-filled" /></template>
<style>
.d_r2di-zt {
  fill: currentColor;
  d: path("M6.5 2A1.5 1.5 0 0 0 5 3.5v13A1.5 1.5 0 0 0 6.5 18h7a1.5 1.5 0 0 0 1.5-1.5v-13A1.5 1.5 0 0 0 13.5 2zM9 14h2a.5.5 0 0 1 0 1H9a.5.5 0 0 1 0-1");
}

</style>

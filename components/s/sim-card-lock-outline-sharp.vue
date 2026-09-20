<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3ljg2bds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sim-card-lock-outline-sharp" /></template>
<style>
.y3ljg2bds {
  fill: currentColor;
  d: path("M9 16h6v-5h-1v-1q0-.825-.587-1.412T12 8t-1.412.588T10 10v1H9zm2-5v-1q0-.425.288-.712T12 9t.713.288T13 10v1zM4 22V8l6-6h10v20zm2-2h12V4h-7.15L6 8.85zm0 0h12z");
}

</style>

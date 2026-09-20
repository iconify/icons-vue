<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v-a_42gfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-add-16-filled" /></template>
<style>
.v-a_42gfc {
  fill: currentColor;
  d: path("M9.626 5.07a5.5 5.5 0 0 0-3.299 1.847A2.751 2.751 0 1 1 9.626 5.07M5.6 8c-.384.75-.6 1.6-.6 2.5c0 1.31.458 2.512 1.222 3.457C3.555 13.653 2 11.803 2 10v-.5A1.5 1.5 0 0 1 3.5 8zm4.9 7a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9m0-7a.5.5 0 0 1 .5.5V10h1.5a.5.5 0 0 1 0 1H11v1.5a.5.5 0 0 1-1 0V11H8.5a.5.5 0 0 1 0-1H10V8.5a.5.5 0 0 1 .5-.5");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v82uz1u_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:star-add-16-filled" /></template>
<style>
.v82uz1u_l {
  fill: currentColor;
  d: path("M8.808 2.101a.9.9 0 0 0-1.614 0L5.673 5.183l-3.401.495a.9.9 0 0 0-.5 1.535l2.462 2.399l-.581 3.387a.9.9 0 0 0 1.306.949l.91-.479a5.5 5.5 0 0 1 4.372-8.463zM15 10.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-4-2a.5.5 0 0 0-1 0V10H8.5a.5.5 0 0 0 0 1H10v1.5a.5.5 0 1 0 1 0V11h1.5a.5.5 0 1 0 0-1H11z");
}

</style>

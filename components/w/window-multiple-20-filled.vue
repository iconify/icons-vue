<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gsachlbem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:window-multiple-20-filled" /></template>
<style>
.gsachlbem {
  fill: currentColor;
  d: path("M4.5 2A2.5 2.5 0 0 0 2 4.5v8A2.5 2.5 0 0 0 4.5 15h8a2.5 2.5 0 0 0 2.5-2.5v-8A2.5 2.5 0 0 0 12.5 2zM3 12.5V6h11v6.5a1.5 1.5 0 0 1-1.5 1.5h-8A1.5 1.5 0 0 1 3 12.5M7.5 18a2.5 2.5 0 0 1-2.45-2h1.035A1.5 1.5 0 0 0 7.5 17H14a3 3 0 0 0 3-3V7.5a1.5 1.5 0 0 0-1-1.415V5.05a2.5 2.5 0 0 1 2 2.45V14a4 4 0 0 1-4 4z");
}

</style>

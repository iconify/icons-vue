<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kooqmxbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-stream-rounded" /></template>
<style>
.kooqmxbsy {
  fill: currentColor;
  d: path("M5.616 18q-.667 0-1.141-.475T4 16.386v-2.27q0-.666.475-1.14t1.14-.475h12.77q.666 0 1.14.475t.475 1.14v2.27q0 .666-.475 1.14t-1.14.475zm0-6.5q-.667 0-1.141-.475T4 9.885v-2.27q0-.666.475-1.14T5.615 6h12.77q.666 0 1.14.475T20 7.615v2.27q0 .666-.475 1.14t-1.14.475z");
}

</style>

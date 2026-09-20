<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o56wjibwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:markdown-copy-sharp" /></template>
<style>
.o56wjibwl {
  fill: currentColor;
  d: path("M7.5 17V3h11v14zm-3 3V6.616h1V19h9.385v1zm5.558-7.308h.884v-4.5h1.616v3h.884v-3h1.616v4.5h.884V7.308h-5.884z");
}

</style>

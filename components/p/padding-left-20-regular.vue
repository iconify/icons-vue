<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yu_d6vbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:padding-left-20-regular" /></template>
<style>
.yu_d6vbsy {
  fill: currentColor;
  d: path("M2 3.5a.5.5 0 0 1 1 0v1a.5.5 0 0 1-1 0zm0 3a.5.5 0 0 1 1 0v2a.5.5 0 0 1-1 0zm0 4a.5.5 0 0 1 1 0v2a.5.5 0 0 1-1 0zm0 4a.5.5 0 0 1 1 0v1a.5.5 0 0 1-1 0zm2.146-4.646a.5.5 0 0 1 0-.708l4.5-4.5a.5.5 0 1 1 .708.708L5.707 9H15.5a.5.5 0 0 1 0 1H5.707l3.647 3.646a.5.5 0 0 1-.708.708zM17 3.5a.5.5 0 0 1 1 0v12a.5.5 0 0 1-1 0z");
}

</style>

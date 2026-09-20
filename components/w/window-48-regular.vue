<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="coho6q2mu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:window-48-regular" /></template>
<style>
.coho6q2mu {
  fill: currentColor;
  d: path("M12.25 6h23.5A6.25 6.25 0 0 1 42 12.25v23.5A6.25 6.25 0 0 1 35.75 42h-23.5A6.25 6.25 0 0 1 6 35.75v-23.5A6.25 6.25 0 0 1 12.25 6M8.5 16.5v19.25a3.75 3.75 0 0 0 3.75 3.75h23.5a3.75 3.75 0 0 0 3.75-3.75V16.5zm31-2.5v-1.75a3.75 3.75 0 0 0-3.75-3.75h-23.5a3.75 3.75 0 0 0-3.75 3.75V14z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x0rm9wq5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:ruler-20-regular" /></template>
<style>
.x0rm9wq5s {
  fill: currentColor;
  d: path("M12.5 2A1.5 1.5 0 0 1 14 3.5v13a1.5 1.5 0 0 1-1.5 1.5h-5A1.5 1.5 0 0 1 6 16.5v-13A1.5 1.5 0 0 1 7.5 2zm-5 1a.5.5 0 0 0-.5.5v1h2.5a.5.5 0 0 1 0 1H7V7h3.5a.5.5 0 0 1 0 1H7v1.5h2.5a.5.5 0 0 1 0 1H7v1.504h3.5a.5.5 0 0 1 0 1H7V14.5h2.5a.5.5 0 0 1 0 1H7v1a.5.5 0 0 0 .5.5h5a.5.5 0 0 0 .5-.5v-13a.5.5 0 0 0-.5-.5z");
}

</style>

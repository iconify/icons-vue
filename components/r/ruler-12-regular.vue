<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="dw5rw5bvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:ruler-12-regular" /></template>
<style>
.dw5rw5bvu {
  fill: currentColor;
  d: path("M7.5 1A1.5 1.5 0 0 1 9 2.5v7A1.5 1.5 0 0 1 7.5 11h-3A1.5 1.5 0 0 1 3 9.5v-7A1.5 1.5 0 0 1 4.5 1zm-3 1a.5.5 0 0 0-.5.5V3h1.5a.5.5 0 0 1 0 1H4v1.5h2.5a.5.5 0 0 1 0 1H4V8h1.5a.5.5 0 0 1 0 1H4v.5a.5.5 0 0 0 .5.5h3a.5.5 0 0 0 .5-.5v-7a.5.5 0 0 0-.5-.5z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u4gl8542i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:next-frame-20-regular" /></template>
<style>
.u4gl8542i {
  fill: currentColor;
  d: path("M4.5 3a.5.5 0 0 1 .5.5v13a.5.5 0 0 1-1 0v-13a.5.5 0 0 1 .5-.5m5.447.214A1.25 1.25 0 0 0 8 4.252v11.5a1.25 1.25 0 0 0 1.954 1.033l8.5-5.793a1.25 1.25 0 0 0-.008-2.07zM9 4.252c0-.2.223-.319.39-.207l8.499 5.707a.25.25 0 0 1 .001.414l-8.5 5.793a.25.25 0 0 1-.39-.207z");
}

</style>

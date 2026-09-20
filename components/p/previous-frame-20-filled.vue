<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fp5zhtb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:previous-frame-20-filled" /></template>
<style>
.fp5zhtb8x {
  fill: currentColor;
  d: path("M15.5 3a.5.5 0 0 0-.5.5v13a.5.5 0 0 0 1 0v-13a.5.5 0 0 0-.5-.5m-5.447.214A1.25 1.25 0 0 1 12 4.252v11.5a1.25 1.25 0 0 1-1.954 1.033l-8.499-5.793a1.25 1.25 0 0 1 .007-2.07z");
}

</style>

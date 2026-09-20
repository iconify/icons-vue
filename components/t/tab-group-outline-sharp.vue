<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9j1aab-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tab-group-outline-sharp" /></template>
<style>
.p9j1aab-o {
  fill: currentColor;
  d: path("M6 18V2h16v16zm2-2h12V8h-7V4H8zm-6 6V6h2v14h14v2zM8 4v12z");
}

</style>

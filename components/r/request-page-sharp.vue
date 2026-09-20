<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1ebcnb4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:request-page-sharp" /></template>
<style>
.d1ebcnb4o {
  fill: currentColor;
  d: path("M11 18h2v-1h2v-5h-4v-1h4V9h-2V8h-2v1H9v5h4v1H9v2h2zm-7 4V2h10l6 6v14z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xttaf1b9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tab-group-outline-sharp" /></template>
<style>
.xttaf1b9n {
  fill: currentColor;
  d: path("M6.5 17V3h14v14zm1-1h12V7.039h-6.23V4H7.5zm-4 4V6.616h1V19h12.385v1zm4-16v12z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8wdhlbvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:park-outline-rounded" /></template>
<style>
.q8wdhlbvo {
  fill: currentColor;
  d: path("M11.012 17H6.393q-.484 0-.717-.429t.04-.833L8.885 11h-.402q-.485 0-.724-.432q-.24-.431.053-.835l3.517-5.058q.13-.18.307-.264q.178-.084.364-.084t.364.084q.176.083.307.264l3.518 5.058q.292.403.052.835q-.239.432-.724.432h-.401l3.167 4.739q.273.403.04.832q-.232.429-.717.429h-4.618v3.27q0 .309-.21.52q-.21.21-.52.21h-.439q-.348 0-.578-.23t-.23-.578zM6.75 16h4h-1.9h6.3h-1.9h4zm0 0h10.5l-4-6h1.9L12 5.5L8.85 10h1.9z");
}

</style>

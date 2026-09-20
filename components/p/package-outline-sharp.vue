<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bffvqy7ok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:package-outline-sharp" /></template>
<style>
.bffvqy7ok {
  fill: currentColor;
  d: path("m10 10.327l2-1l2 1V5h-4zM7 16.5v-1h5v1zM4 20V4h16v16zM5 5v14zm0 14h14V5h-4v6.962l-3-1.5l-3 1.5V5H5z");
}

</style>

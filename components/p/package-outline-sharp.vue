<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="znjqt9xba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:package-outline-sharp" /></template>
<style>
.znjqt9xba {
  fill: currentColor;
  d: path("m10 9.75l2-1l2 1V5h-4zM7 17v-2h5v2zm-4 4V3h18v18zM5 5v14zm0 14h14V5h-3v8l-4-2l-4 2V5H5z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcf3kebdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:settings-input-component-outline-sharp" /></template>
<style>
.bcf3kebdt {
  fill: currentColor;
  d: path("M3 23v-4.15l-2-2V6h2V1h2v5h2v10.85l-2 2V23zm8 0v-4.15l-2-2V6h2V1h2v5h2v10.85l-2 2V23zm8 0v-4.15l-2-2V6h2V1h2v5h2v10.85l-2 2V23zM3 8v4h2V8zm8 0v4h2V8zm8 0v4h2V8zM4 17l1-1v-2H3v2zm8 0l1-1v-2h-2v2zm8 0l1-1v-2h-2v2zm0-4");
}

</style>

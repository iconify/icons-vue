<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhy1nsk7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:settings-input-component-sharp" /></template>
<style>
.yhy1nsk7q {
  fill: currentColor;
  d: path("M3 23v-4.15l-2-2V14h6v2.85l-2 2V23zm8 0v-4.15l-2-2V14h6v2.85l-2 2V23zm8 0v-4.15l-2-2V14h6v2.85l-2 2V23zM1 12V6h2V1h2v5h2v6zm8 0V6h2V1h2v5h2v6zm8 0V6h2V1h2v5h2v6z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmj7r7trx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:upload-file-sharp" /></template>
<style>
.hmj7r7trx {
  fill: currentColor;
  d: path("M11 19h2v-4.175l1.6 1.6L16 15l-4-4l-4 4l1.425 1.4L11 14.825zm-7 3V2h10l6 6v14zm9-13h5l-5-5z");
}

</style>

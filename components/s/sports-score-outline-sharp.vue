<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oio_tbbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sports-score-outline-sharp" /></template>
<style>
.oio_tbbwi {
  fill: currentColor;
  d: path("M9 6h2V4H9zm4 0V4h2v2zm-4 8v-2h2v2zm8-4V8h2v2zm0 4v-2h2v2zm-4 0v-2h2v2zm4-8V4h2v2zm-6 2V6h2v2zM5 20V4h2v2h2v2H7v2h2v2H7v8zm10-8v-2h2v2zm-4 0v-2h2v2zm-2-2V8h2v2zm4 0V8h2v2zm2-2V6h2v2z");
}

</style>

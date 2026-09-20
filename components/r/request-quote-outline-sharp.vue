<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2o2zfnpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:request-quote-outline-sharp" /></template>
<style>
.b2o2zfnpt {
  fill: currentColor;
  d: path("M11 19h2v-1h2v-5h-4v-1h4v-2h-2V9h-2v1H9v5h4v1H9v2h2zm-7 3V2h11l5 5v15zm2-2h12V8h-4V4H6zM6 4v4zv16z");
}

</style>

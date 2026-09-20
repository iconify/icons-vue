<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imko2zvxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:request-quote-sharp" /></template>
<style>
.imko2zvxe {
  fill: currentColor;
  d: path("M11 19h2v-1h2v-5h-4v-1h4v-2h-2V9h-2v1H9v5h4v1H9v2h2zm-7 3V2h11l5 5v15zm2-2h12V8h-4V4H6zM6 4h8v4h4l-4-4v4h4v12H6z");
}

</style>

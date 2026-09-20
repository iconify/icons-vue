<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r605z-emy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:plug-connect-outline-sharp" /></template>
<style>
.r605z-emy {
  fill: currentColor;
  d: path("M7 20v-1H3v-6H1v-2h2V5h4V4h2v16zm-2-3h2V7H5zm10 3v-4h-4v-2h4v-4h-4V8h4V4h2v1h4v6h2v2h-2v6h-4v1zm2-3h2V7h-2zm0-5");
}

</style>

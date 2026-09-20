<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcmprk0la"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stream-apps-outline-sharp" /></template>
<style>
.bcmprk0la {
  fill: currentColor;
  d: path("M16 13h5v-3h-5zm-2 4V8h9v7h-7zm-9 6V1h14v6h-2V6H7v12h10v-1h2v6zm2-3v1h10v-1zM7 4h10V3H7zm0 0V3zm0 16v1zm9-7v-3z");
}

</style>

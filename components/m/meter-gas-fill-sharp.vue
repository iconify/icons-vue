<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sb2_1pblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:meter-gas-fill-sharp" /></template>
<style>
.sb2_1pblv {
  fill: currentColor;
  d: path("M4 13H3a1 1 0 0 1 0-2h1V3a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v8h1a1 1 0 0 1 0 2h-1v8a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1Zm8.981-6.596a1.002 1.002 0 0 0-1.606-.585c-1.551 1.242-2.428 2.91-1.469 4.828q.099.195.206.385c.2.359.288.546.288.968a.2.2 0 0 1-.4 0a.999.999 0 0 0-1.707-.707c-.649.649-.893 1.613-.893 2.507c0 1.22.485 2.39 1.347 3.253a4.604 4.604 0 0 0 6.506 0A4.6 4.6 0 0 0 16.6 13.8c0-1.6-.324-3.138-1.493-4.307A1 1 0 0 0 15 9.4c-1.007-.756-1.768-1.743-2.019-2.996");
}

</style>

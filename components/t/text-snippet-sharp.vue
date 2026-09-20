<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k08jmb_yn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:text-snippet-sharp" /></template>
<style>
.k08jmb_yn {
  fill: currentColor;
  d: path("M4 20V4h10.789L20 9.211V20zm3.5-4h9v-1h-9zm0-3.5h9v-1h-9zm0-3.5h5.73V8H7.5z");
}

</style>

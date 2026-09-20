<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1hz5jbyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:straighten-outline-sharp" /></template>
<style>
.h1hz5jbyj {
  fill: currentColor;
  d: path("M2 18V6h20v12zm2-2h16V8h-3v4h-2V8h-2v4h-2V8H9v4H7V8H4zm3-4h2zm4 0h2zm4 0h2zm-3 0");
}

</style>

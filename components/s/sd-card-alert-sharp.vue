<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1v8azb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sd-card-alert-sharp" /></template>
<style>
.f1v8azb5r {
  fill: currentColor;
  d: path("M11 17h2v-2h-2zm0-4h2V8h-2zm9 9H4V8l6-6h10z");
}

</style>

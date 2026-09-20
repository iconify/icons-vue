<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkpdywbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:subscriptions-sharp" /></template>
<style>
.mkpdywbcb {
  fill: currentColor;
  d: path("M2 22V8h20v14zm8-3l6-4l-6-4zM4 7V5h16v2zm3-3V2h10v2z");
}

</style>

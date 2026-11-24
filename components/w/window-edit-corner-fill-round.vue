<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7ahirvrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-edit-corner-fill-round" /></template>
<style>
.f7ahirvrs {
  fill: currentColor;
  d: path("M4 9v7a3 3 0 0 0 3 3h1a1 1 0 0 1 0 2H7a5 5 0 0 1-5-5V8a5 5 0 0 1 5-5h10c1.33 0 2.597.522 3.536 1.464A5 5 0 0 1 22 8a1 1 0 0 1-1 1Zm8 12v-3c0-.265.105-.52.293-.707l5-5a1 1 0 0 1 1.414 0l3 3a1 1 0 0 1 0 1.414l-5 5A1 1 0 0 1 16 22h-3a1 1 0 0 1-1-1");
}

</style>

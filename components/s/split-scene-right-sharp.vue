<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydc3gto7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:split-scene-right-sharp" /></template>
<style>
.ydc3gto7h {
  fill: currentColor;
  d: path("M3 20V4h6v16zm8 2V2h2v2h8v16h-8v2z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y9-2_pb6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:teardrop-bottom-right-32-filled" /></template>
<style>
.y9-2_pb6n {
  fill: currentColor;
  d: path("M2 16C2 8.268 8.268 2 16 2s14 6.268 14 14v10.75A3.25 3.25 0 0 1 26.75 30H16C8.268 30 2 23.732 2 16");
}

</style>

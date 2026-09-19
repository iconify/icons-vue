<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2mhlqndk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-30fps" /></template>
<style>
.z2mhlqndk {
  fill: currentColor;
  d: path("M2 5v3h6v2.5H3v3h5V16H2v3h9V5zm17 3v8h-4V8zm3-3H12v14h10z");
}

</style>

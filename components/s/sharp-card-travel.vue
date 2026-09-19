<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kho8-cb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-card-travel" /></template>
<style>
.kho8-cb4f {
  fill: currentColor;
  d: path("M22 6h-5V4c0-1.1-.9-2-2-2H9c-1.1 0-2 .9-2 2v2H2v15h20zM9 4h6v2H9zm11 15H4v-2h16zm0-5H4V8h3v2h2V8h6v2h2V8h3z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ju72-ipxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-sms-failed" /></template>
<style>
.ju72-ipxf {
  fill: currentColor;
  d: path("M22 2H2v20l4-4h16zm-9 12h-2v-2h2zm0-4h-2V6h2z");
}

</style>

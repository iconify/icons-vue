<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9vp2pb8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-medical-services" /></template>
<style>
.x9vp2pb8n {
  fill: currentColor;
  d: path("M16 6V2H8v4H2v16h20V6zm-6-2h4v2h-4zm6 11h-3v3h-2v-3H8v-2h3v-3h2v3h3z");
}

</style>

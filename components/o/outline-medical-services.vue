<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ic-f6qblm"/><path class="ox5bagm_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-medical-services" /></template>
<style>
.ic-f6qblm {
  fill: currentColor;
  d: path("M20 6h-4V4c0-1.1-.9-2-2-2h-4c-1.1 0-2 .9-2 2v2H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V8c0-1.1-.9-2-2-2M10 4h4v2h-4zm10 16H4V8h16z");
}

.ox5bagm_m {
  fill: currentColor;
  d: path("M13 10h-2v3H8v2h3v3h2v-3h3v-2h-3z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d65oxlv4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pentagon-outline-sharp" /></template>
<style>
.d65oxlv4h {
  fill: currentColor;
  d: path("M7.45 19h9.1l3.075-9.225L12 4.45L4.375 9.775zM6 21L2 9l10-7l10 7l-4 12zm6-9.275");
}

</style>

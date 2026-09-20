<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bns3iyn4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:vehicle-rv-20-regular" /></template>
<style>
.bns3iyn4x {
  fill: currentColor;
  d: path("M16 3a2 2 0 0 1 2 2v1a1 1 0 0 1-1 1h-.778l1.136 3.034A2 2 0 0 1 19 12v1a2 2 0 0 1-2 2h-.05a2.501 2.501 0 0 1-4.9 0h-3.1a2.501 2.501 0 0 1-4.9 0H4a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2zM6.5 13a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3m8 0a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3M3 13a1 1 0 0 0 1 1h.05a2.501 2.501 0 0 1 4.9 0h3.1a2.501 2.501 0 0 1 4.9 0H17a1 1 0 0 0 1-1v-1a1 1 0 0 0-1-1H3zm1-9a1 1 0 0 0-1 1v5h8V8a2 2 0 0 1 2-2h4V5a1 1 0 0 0-1-1zm9 3a1 1 0 0 0-1 1v2h4.278l-1.125-3zM8 5a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1H5a1 1 0 0 1-.995-.897L4 8V6a1 1 0 0 1 1-1zM5 8h3V6H5z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p0a-6zb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:vehicle-rv-20-filled" /></template>
<style>
.p0a-6zb-a {
  fill: currentColor;
  d: path("M16 3a2 2 0 0 1 2 2v1a1 1 0 0 1-1 1h-.778l1.136 3.034A2 2 0 0 1 19 12v1a2 2 0 0 1-2 2h-.05a2.501 2.501 0 0 1-4.9 0h-3.1a2.501 2.501 0 0 1-4.9 0H4a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2zM6.5 13a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3m8 0a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3M5 6a1 1 0 0 0-1 1v2l.005.103A1 1 0 0 0 5 10h3a1 1 0 0 0 1-1V7a1 1 0 0 0-1-1zm8 1a1 1 0 0 0-1 1v2h4.278l-1.125-3z");
}

</style>

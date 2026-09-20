<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-5bhacyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:text-rotate-up-sharp" /></template>
<style>
.l-5bhacyb {
  fill: currentColor;
  d: path("M19 20h-2V6.8l-1.05 1.05l-1.4-1.4L18 3l3.5 3.45l-1.45 1.4L19 6.8zm-5-2.9L3 13v-2l11-4.1v1.9l-2.8.95v4.45l2.8 1zm-4.4-3.45v-3.3l-4.55 1.6v.1z");
}

</style>

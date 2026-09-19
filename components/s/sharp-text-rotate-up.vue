<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epxcdol0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-text-rotate-up" /></template>
<style>
.epxcdol0p {
  fill: currentColor;
  d: path("m18 4l-3 3h2v13h2V7h2zm-6.2 11.5v-5l2.2-.9V7.5L3 12.25v1.5l11 4.75v-2.1zM4.98 13L10 11.13v3.74z");
}

</style>

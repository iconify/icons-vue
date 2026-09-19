<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q32tawu3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-settings-phone" /></template>
<style>
.q32tawu3h {
  fill: currentColor;
  d: path("M13.21 17.37a15.05 15.05 0 0 1-6.59-6.59l2.53-2.53L8.54 3H3.03C2.45 13.18 10.82 21.55 21 20.97v-5.51l-5.27-.61zM11 9h2v2h-2zm4 0h2v2h-2zm4 0h2v2h-2z");
}

</style>

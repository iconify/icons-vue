<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fhth5obrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-play-sharp-fill" /></template>
<style>
.fhth5obrt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 2L21 2C21.5523 2 22 2.4477 22 3L22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21L2 3C2 2.4477 2.4477 2 3 2ZM9.4927 6.4533L17.0107 11.152C17.6374 11.5437 17.6374 12.4563 17.0107 12.848L9.4927 17.5467C8.8266 17.963 7.9627 17.4841 7.9627 16.6987L7.9627 7.3013C7.9627 6.5159 8.8266 6.037 9.4927 6.4533Z");
}

</style>

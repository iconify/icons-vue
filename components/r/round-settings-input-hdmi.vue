<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fz30mtbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-settings-input-hdmi" /></template>
<style>
.fz30mtbdv {
  fill: currentColor;
  d: path("M18 7V4c0-1.1-.9-2-2-2H8c-1.1 0-2 .9-2 2v3c-.55 0-1 .45-1 1v4.7c0 .2.06.39.17.55L8 19v2c0 .55.45 1 1 1h6c.55 0 1-.45 1-1v-2l2.83-5.75a1 1 0 0 0 .17-.55V8c0-.55-.45-1-1-1m-2 0h-2V5.5c0-.28-.22-.5-.5-.5s-.5.22-.5.5V7h-2V5.5c0-.28-.22-.5-.5-.5s-.5.22-.5.5V7H8V4h8z");
}

</style>

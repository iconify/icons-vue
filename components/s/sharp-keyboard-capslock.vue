<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d85607bpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-keyboard-capslock" /></template>
<style>
.d85607bpn {
  fill: currentColor;
  d: path("M12 8.41L16.59 13L18 11.59l-6-6l-6 6L7.41 13zM6 18h12v-2H6z");
}

</style>

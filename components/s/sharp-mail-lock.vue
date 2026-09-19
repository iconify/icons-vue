<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yw2rj7a9a"/><path class="den27bbpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-mail-lock" /></template>
<style>
.den27bbpl {
  fill: currentColor;
  d: path("M23 15v-.89c0-1-.68-1.92-1.66-2.08A2 2 0 0 0 19 14v1h-1v5h6v-5zm-1 0h-2v-1c0-.55.45-1 1-1s1 .45 1 1z");
}

.yw2rj7a9a {
  fill: currentColor;
  d: path("M22 9.97V4H2.01L2 20h14v-5.03c0-2.76 2.24-5 5-5zM20 8l-8 5l-8-5V6l8 5l8-5z");
}

</style>

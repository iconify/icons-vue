<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0o8p05fd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:terminal-2-rounded" /></template>
<style>
.x0o8p05fd {
  fill: currentColor;
  d: path("M13 20q-.425 0-.712-.288T12 19t.288-.712T13 18h6q.425 0 .713.288T20 19t-.288.713T19 20zM8.675 10L4.8 6.125q-.3-.3-.3-.712t.3-.713t.7-.3t.7.3l4.6 4.6q.3.3.3.7t-.3.7l-4.6 4.6q-.3.3-.7.3t-.7-.3t-.3-.712t.3-.713z");
}

</style>

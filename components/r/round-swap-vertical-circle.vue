<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv77ikblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-swap-vertical-circle" /></template>
<style>
.pv77ikblg {
  fill: currentColor;
  d: path("M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10s10-4.48 10-10S17.52 2 12 2M6.5 9l3.15-3.15c.2-.2.51-.2.71 0L13.5 9H11v4H9V9zm7.85 9.15c-.2.2-.51.2-.71 0L10.5 15H13v-4h2v4h2.5z");
}

</style>

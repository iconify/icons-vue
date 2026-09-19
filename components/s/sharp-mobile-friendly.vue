<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqrwpn4iq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-mobile-friendly" /></template>
<style>
.cqrwpn4iq {
  fill: currentColor;
  d: path("M21 1H7v5h2V4h10v16H9v-2H7v5h14zM7.01 13.47l-2.55-2.55l-1.27 1.27L7 16l7.19-7.19l-1.27-1.27z");
}

</style>

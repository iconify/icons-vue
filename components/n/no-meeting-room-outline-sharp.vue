<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kq4iajbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:no-meeting-room-outline-sharp" /></template>
<style>
.kq4iajbzj {
  fill: currentColor;
  d: path("m19 16.15l-2-2V6h-2v6.15l-2-2V5H7.85l-2-2H15v1h4zm.8 6.45L15 17.8V21H3v-2h2V7.8L1.4 4.2l1.4-1.4l18.4 18.4zM7 19h6v-3.2l-6-6zm3-6.2");
}

</style>

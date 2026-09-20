<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wf9sm3bxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:power-plug-outline-sharp" /></template>
<style>
.wf9sm3bxc {
  fill: currentColor;
  d: path("M11.27 19h1.46v-2.08L16 13.65V9H8v4.65l3.27 3.27zm-1 1v-2.654L7 14.077V8h2.346V4h1v4h3.308V4h1v4H17v6.077l-3.27 3.27V20zM12 14");
}

</style>

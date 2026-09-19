<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgr05pb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-picture-as-pdf" /></template>
<style>
.sgr05pb_l {
  fill: currentColor;
  d: path("M20 2H8c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2m0 14H8V4h12zM4 6H2v14c0 1.1.9 2 2 2h14v-2H4zm12 6V9c0-.55-.45-1-1-1h-2v5h2c.55 0 1-.45 1-1m-2-3h1v3h-1zm4 2h1v-1h-1V9h1V8h-2v5h1zm-8 0h1c.55 0 1-.45 1-1V9c0-.55-.45-1-1-1H9v5h1zm0-2h1v1h-1z");
}

</style>

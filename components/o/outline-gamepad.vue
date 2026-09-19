<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgylfp4se"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-gamepad" /></template>
<style>
.bgylfp4se {
  fill: currentColor;
  d: path("M13 4v2.67l-1 1l-1-1V4zm7 7v2h-2.67l-1-1l1-1zM6.67 11l1 1l-1 1H4v-2zM12 16.33l1 1V20h-2v-2.67zM15 2H9v5.5l3 3l3-3zm7 7h-5.5l-3 3l3 3H22zM7.5 9H2v6h5.5l3-3zm4.5 4.5l-3 3V22h6v-5.5z");
}

</style>

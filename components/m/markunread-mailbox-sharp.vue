<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ar-oh8bhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:markunread-mailbox-sharp" /></template>
<style>
.ar-oh8bhs {
  fill: currentColor;
  d: path("M3 21V9h3.616V3h6.5v3.616h-5.5V14H10V9h11v12z");
}

</style>

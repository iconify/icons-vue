<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eeat6ppar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-flight-takeoff" /></template>
<style>
.eeat6ppar {
  fill: currentColor;
  d: path("M20.5 19h-17c-.55 0-1 .45-1 1s.45 1 1 1h17c.55 0 1-.45 1-1s-.45-1-1-1m1.57-9.36c-.22-.8-1.04-1.27-1.84-1.06L14.92 10L8.46 3.98a1.06 1.06 0 0 0-1.02-.25c-.68.19-1 .97-.65 1.58l3.44 5.96l-4.97 1.33l-1.57-1.24c-.25-.19-.57-.26-.88-.18l-.33.09c-.32.08-.47.45-.3.73l1.88 3.25c.23.39.69.58 1.12.47L21 11.48c.8-.22 1.28-1.04 1.07-1.84");
}

</style>

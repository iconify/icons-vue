<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhgy9cx9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-king-bed" /></template>
<style>
.nhgy9cx9j {
  fill: currentColor;
  d: path("M20 10V5H4v5H2v7h1.33L4 19h1l.67-2h12.67l.66 2h1l.67-2H22v-7zm-9 0H6V7h5zm7 0h-5V7h5z");
}

</style>

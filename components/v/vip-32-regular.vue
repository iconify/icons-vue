<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a8000iaib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:vip-32-regular" /></template>
<style>
.a8000iaib {
  fill: currentColor;
  d: path("M25.5 4A4.5 4.5 0 0 1 30 8.5v15a4.5 4.5 0 0 1-4.5 4.5h-19A4.5 4.5 0 0 1 2 23.5v-15A4.5 4.5 0 0 1 6.5 4zm-19 2A2.5 2.5 0 0 0 4 8.5v15A2.5 2.5 0 0 0 6.5 26h19a2.5 2.5 0 0 0 2.5-2.5v-15A2.5 2.5 0 0 0 25.5 6zm5.07 6.135a1 1 0 0 1 1.86.73l-2.657 6.768a1.367 1.367 0 0 1-2.545 0l-2.659-6.768a1 1 0 0 1 1.862-.73L9.5 17.402zM16 11.5a1 1 0 0 1 1 1v7a1 1 0 1 1-2 0v-7a1 1 0 0 1 1-1m6.75 0a3.25 3.25 0 0 1 0 6.5H21v1.5a1 1 0 1 1-2 0v-7a1 1 0 0 1 1-1zM21 16h1.75a1.25 1.25 0 1 0 0-2.5H21z");
}

</style>

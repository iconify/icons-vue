<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw2zkmbpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-atm" /></template>
<style>
.iw2zkmbpw {
  fill: currentColor;
  d: path("M8 9v1.5h2.25V15h1.5v-4.5H14V9zM7 9H2v6h1.5v-1.5h2V15H7zm-1.5 3h-2v-1.5h2zM22 9h-6.5v6H17v-4.5h1V14h1.5v-3.51h1V15H22z");
}

</style>

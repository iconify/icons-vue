<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uioqj7bms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:splitscreen-sharp" /></template>
<style>
.uioqj7bms {
  fill: currentColor;
  d: path("M4 10.635V4h16v6.635zM4 20v-6.615h16V20z");
}

</style>

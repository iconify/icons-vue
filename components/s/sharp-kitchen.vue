<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cui74ac_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-kitchen" /></template>
<style>
.cui74ac_d {
  fill: currentColor;
  d: path("M20 2.01L4 2v20h16zM18 20H6v-9.02h12zm0-11H6V4h12zM8 5h2v3H8zm0 7h2v5H8z");
}

</style>

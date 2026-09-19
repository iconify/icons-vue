<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxrb5nb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-approval" /></template>
<style>
.oxrb5nb_m {
  fill: currentColor;
  d: path("M4 14v8h16v-8zm14 4H6v-2h12zM12 2C9.24 2 7 4.24 7 7l5 7l5-7c0-2.76-2.24-5-5-5");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ho_tg7biz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tab-move-outline-sharp" /></template>
<style>
.ho_tg7biz {
  fill: currentColor;
  d: path("M4 20v-4.038h1V19h14V7.154H5v3.038H4V4h16v16zm7.116-3.134l-.689-.689l2.556-2.6H4v-1h8.983l-2.556-2.6l.689-.688l3.788 3.788z");
}

</style>

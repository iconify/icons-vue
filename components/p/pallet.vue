<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b9q98gn2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pallet" /></template>
<style>
.b9q98gn2g {
  fill: currentColor;
  d: path("M3.885 19.577v-2h16.23v2h-1.769v-1h-5.461v1h-1.77v-1h-5.46v1zm2.942-4q-.343 0-.575-.232t-.233-.576V4.385q0-.344.232-.576q.233-.232.576-.232h10.346q.343 0 .576.232t.232.576v10.23q0 .409-.266.686q-.265.276-.657.276zM9 8.154h6v-1H9z");
}

</style>

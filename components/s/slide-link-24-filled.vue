<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bz-buw4zd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slide-link-24-filled" /></template>
<style>
.bz-buw4zd {
  fill: currentColor;
  d: path("M19.25 13.5a3.75 3.75 0 0 1 .202 7.495l-.198.005v.005a.75.75 0 0 1-.11-1.493l.102-.007l.004-.005a2.25 2.25 0 0 0 .154-4.495L19.25 15a.75.75 0 0 1-.102-1.493zm-3.5 0a.75.75 0 0 1 .102 1.493L15.75 15a2.25 2.25 0 0 0-.154 4.495l.154.005a.75.75 0 0 1 .102 1.493L15.75 21a3.75 3.75 0 0 1-.2-7.495zm3-9.5A3.25 3.25 0 0 1 22 7.25v6.128a4.73 4.73 0 0 0-2.75-.878h-3.5a4.75 4.75 0 0 0-3.872 7.5H5.25A3.25 3.25 0 0 1 2 16.75v-9.5A3.25 3.25 0 0 1 5.25 4zm.5 12.5a.75.75 0 0 1 .102 1.493L19.25 18h-3.5a.75.75 0 0 1-.102-1.493l.102-.007z");
}

</style>

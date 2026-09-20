<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ox5zd0b0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slide-link-24-regular" /></template>
<style>
.ox5zd0b0v {
  fill: currentColor;
  d: path("M19.25 13.5a3.75 3.75 0 0 1 .202 7.495l-.198.005v.005a.75.75 0 0 1-.11-1.493l.102-.007l.004-.005a2.25 2.25 0 0 0 .154-4.495L19.25 15a.75.75 0 0 1-.102-1.493zm-3.5 0a.75.75 0 0 1 .102 1.493L15.75 15a2.25 2.25 0 0 0-.154 4.495l.154.005a.75.75 0 0 1 .102 1.493L15.75 21a3.75 3.75 0 0 1-.2-7.495zm3-9.5A3.25 3.25 0 0 1 22 7.25v6.128a4.7 4.7 0 0 0-1.5-.711V7.25a1.75 1.75 0 0 0-1.75-1.75H5.25A1.75 1.75 0 0 0 3.5 7.25v9.5c0 .966.784 1.75 1.75 1.75h5.917a4.7 4.7 0 0 0 .71 1.5H5.25A3.25 3.25 0 0 1 2 16.75v-9.5A3.25 3.25 0 0 1 5.25 4zm.5 12.5a.75.75 0 0 1 .102 1.493L19.25 18h-3.5a.75.75 0 0 1-.102-1.493l.102-.007z");
}

</style>

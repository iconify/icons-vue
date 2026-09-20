<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="pc9_gdr2j"/><path class="iabhwuu1j"/><path class="fjqvuuhvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:optical-disk" /></template>
<style>
.fjqvuuhvb {
  fill: var(--svg-color--f5f8fa, #f5f8fa);
  d: path("m18.527 22.712l1.251 11.183a15.95 15.95 0 0 0 9.536-4.582l-7.944-7.944a4.75 4.75 0 0 1-2.843 1.343m-1.023-9.427L16.325 2.089a15.95 15.95 0 0 0-9.639 4.598l7.944 7.944a4.75 4.75 0 0 1 2.874-1.346");
}

.iabhwuu1j {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M13.288 17.476a4.74 4.74 0 0 1 1.343-2.846L6.686 6.686a15.95 15.95 0 0 0-4.584 9.547zm9.425 1.048a4.74 4.74 0 0 1-1.343 2.846l7.944 7.944a15.95 15.95 0 0 0 4.584-9.547z");
}

.pc9_gdr2j {
  fill: var(--svg-color--8899a6, #8899a6);
  d: path("M36 18c0 9.941-8.059 18-18 18S0 27.941 0 18S8.059 0 18 0s18 8.059 18 18m-18-3a3 3 0 1 0 0 6a3 3 0 0 0 0-6");
}

</style>

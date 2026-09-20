<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="szfhcbbef"/><path class="hpk4e3bbr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mod" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hpk4e3bbr {
  fill: var(--svg-color--253750, #253750);
  d: path("m5.25 21l8.804-8.957L5.556 3.41L5.25 3.1z");
}

.szfhcbbef {
  fill: var(--svg-color--4283eb, #4283eb);
  d: path("M11.902 9.936L18.75 16.9V3z");
}

</style>

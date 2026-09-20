<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vr-2xgv-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-warning-32-light" /></template>
<style>
.vr-2xgv-r {
  fill: currentColor;
  d: path("M19.958 6H6.5A3.5 3.5 0 0 0 3 9.5v.707l13 7.221l4.37-2.427h2.06l-6.187 3.437a.5.5 0 0 1-.486 0L3 11.35V22.5A3.5 3.5 0 0 0 6.5 26h19a3.5 3.5 0 0 0 3.5-3.5V15h.503q.258 0 .497-.048V22.5a4.5 4.5 0 0 1-4.5 4.5h-19A4.5 4.5 0 0 1 2 22.5v-13A4.5 4.5 0 0 1 6.5 5h13.959zm3.206-4.172c.553-1.104 2.12-1.104 2.672 0l5.002 9.992c.5 1-.222 2.18-1.336 2.18H19.498c-1.114 0-1.837-1.18-1.336-2.18zM24.5 11a.5.5 0 1 0 0 1a.5.5 0 0 0 0-1m0-7a.5.5 0 0 0-.5.5v5a.5.5 0 0 0 1 0v-5a.5.5 0 0 0-.5-.5");
}

</style>

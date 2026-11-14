<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m88ta1een"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:save-edit-32-filled" /></template>
<style>
.m88ta1een {
  fill: currentColor;
  d: path("M25.572 16.35a2.88 2.88 0 0 1 4.144.057a2.883 2.883 0 0 1-.072 4.018l-8.609 8.543c-.351.349-.79.597-1.27.72l-3.019.779a1 1 0 0 1-1.217-1.22l.79-3.052a2.66 2.66 0 0 1 .686-1.205zm-9.627 7.584a4.16 4.16 0 0 0-1.073 1.885l-.79 3.052q-.016.064-.028.129H9V18.5a.5.5 0 0 1 .5-.5h12.328zM9 9.5a2.5 2.5 0 0 0 2.5 2.5h8A2.5 2.5 0 0 0 22 9.5V3.022a4.5 4.5 0 0 1 2.732 1.296l2.95 2.95A4.5 4.5 0 0 1 29 10.45v3.77a4.38 4.38 0 0 0-4.488 1.074l-.942.95A2.5 2.5 0 0 0 22.5 16h-13A2.5 2.5 0 0 0 7 18.5v10.473A4.5 4.5 0 0 1 3 24.5v-17A4.5 4.5 0 0 1 7.5 3H9zm11 0a.5.5 0 0 1-.5.5h-8a.5.5 0 0 1-.5-.5V3h9z");
}

</style>

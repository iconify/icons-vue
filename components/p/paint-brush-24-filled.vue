<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iku63s8ok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:paint-brush-24-filled" /></template>
<style>
.iku63s8ok {
  fill: currentColor;
  d: path("M12.5 2v3.252a.75.75 0 0 0 1.5 0V2h1v4.251a.75.75 0 0 0 1.5 0V2h1.75a.75.75 0 0 1 .75.75V11H5V2.75A.75.75 0 0 1 5.75 2zM5 12.5v1.752a2.25 2.25 0 0 0 2.25 2.25H10V20a2 2 0 1 0 4 0v-3.498h2.75a2.25 2.25 0 0 0 2.25-2.25V12.5z");
}

</style>

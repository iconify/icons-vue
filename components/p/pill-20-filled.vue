<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iel7xpc0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pill-20-filled" /></template>
<style>
.iel7xpc0i {
  fill: currentColor;
  d: path("M11.147 3.147a4.036 4.036 0 1 1 5.707 5.707l-8 8a4.035 4.035 0 1 1-5.707-5.707zm5 .707a3.036 3.036 0 0 0-4.293 0L8.207 7.5l4.293 4.293l3.647-3.646a3.035 3.035 0 0 0 0-4.293M8.854 14.147a.5.5 0 0 0-.707 0l-1.5 1.5a.914.914 0 0 1-1.293 0A.498.498 0 0 0 4.5 16a.5.5 0 0 0 .15.357a1.914 1.914 0 0 0 2.704-.003l1.5-1.5a.5.5 0 0 0 0-.707");
}

</style>

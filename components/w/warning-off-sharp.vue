<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfxawabvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:warning-off-sharp" /></template>
<style>
.rfxawabvk {
  fill: currentColor;
  d: path("M12.434 17.434q.182-.182.182-.434t-.182-.434t-.434-.181t-.434.181t-.181.434t.181.434t.434.181t.434-.181m6.691-1.134l-9.02-9.02L12 4zm1.158 5.404L18.579 20H2.73L8.55 9.971L2.271 3.692l.714-.713L20.996 20.99zm-8.783-6.32h.81v-1.653l-.81-.81z");
}

</style>

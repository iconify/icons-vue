<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_3f1u_fr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:turn-sharp-right-outline-sharp" /></template>
<style>
.p_3f1u_fr {
  fill: currentColor;
  d: path("M6.5 20v-6.884h10v-7.2l-2.1 2.1l-.708-.708L17 4l3.308 3.308l-.708.708l-2.1-2.1v8.2h-10V20z");
}

</style>

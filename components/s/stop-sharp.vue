<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c24gsgbav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stop-sharp" /></template>
<style>
.c24gsgbav {
  fill: currentColor;
  d: path("M7 17V7h10v10z");
}

</style>

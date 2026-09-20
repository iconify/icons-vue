<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqlzelb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-lock-portrait-sharp" /></template>
<style>
.dqlzelb4i {
  fill: currentColor;
  d: path("M5 23V1h14v5.1h1v4.8h-1V23zm4-7h6v-5h-1v-1q0-.825-.587-1.412T12 8t-1.412.588T10 10v1H9zm2-5v-1q0-.425.288-.712T12 9t.713.288T13 10v1z");
}

</style>

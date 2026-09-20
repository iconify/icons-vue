<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bysp5t_fv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shift-lock-sharp" /></template>
<style>
.bysp5t_fv {
  fill: currentColor;
  d: path("M9 16.616v-3.847H5.115L12 3.577l6.885 9.192H15v3.846zM5 20v-1h14v1z");
}

</style>

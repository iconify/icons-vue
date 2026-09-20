<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jixoakntt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:picture-in-picture-large-outline-sharp" /></template>
<style>
.jixoakntt {
  fill: currentColor;
  d: path("M5.923 15.616V5.923h11.693v9.693zM3 19v-1h17V5h1v14z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="num-5bb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:subject-sharp" /></template>
<style>
.num-5bb5o {
  fill: currentColor;
  d: path("M5 18.23V17h8v1zm0-3.788v-1h14v1zm0-3.884v-1h14v1zM5 7V5.77h14V7z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pz0-jl4_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:remove-selection-outline-sharp" /></template>
<style>
.pz0-jl4_a {
  fill: currentColor;
  d: path("M4 17v-2h1v2zm0-4v-2h1v2zm0-4V7h1v2zm3 11v-1h2v1zM7 5V4h2v1zm4 0V4h2v1zm1.192 15l-.708-.708l3.55-3.55l-3.55-3.55l.708-.708l3.55 3.55l3.55-3.55l.708.708l-3.55 3.55l3.55 3.55l-.708.708l-3.55-3.55zM15 5V4h2v1zm4 4V7h1v2zM4 5V4h1v1zm16 0h-1V4h1zM4 20v-1h1v1z");
}

</style>

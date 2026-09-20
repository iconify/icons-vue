<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nw2rdv9fo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:switch-left-sharp" /></template>
<style>
.nw2rdv9fo {
  fill: currentColor;
  d: path("M10 17.48L4.52 12L10 6.52zm-.885-2.124V8.644L5.76 12zM14 17.48V6.519L19.48 12z");
}

</style>

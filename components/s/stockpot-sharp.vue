<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tad0vib8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stockpot-sharp" /></template>
<style>
.tad0vib8r {
  fill: currentColor;
  d: path("M4 19V7.98h16V19zM4 6.596v-1h5.5V4h5v1.596H20v1z");
}

</style>

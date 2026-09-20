<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sctaskb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:video-call-sharp" /></template>
<style>
.sctaskb6z {
  fill: currentColor;
  d: path("M9.98 15.5h1v-3h3v-1h-3v-3h-1v3h-3v1h3zM3.48 19V5h14v6.27l3.04-3.04v7.54l-3.04-3.04V19z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ounswac7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:split-scene-2-outline-sharp" /></template>
<style>
.ounswac7d {
  fill: currentColor;
  d: path("M5 20v-5.115h1V19h12v-4.115h1V20zm-2-7.5v-1h2V4h14v7.5h2v1zm3-1h12V5H6zM18 19H6zm0-14H6z");
}

</style>

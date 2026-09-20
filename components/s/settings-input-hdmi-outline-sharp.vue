<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzfe4bbaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:settings-input-hdmi-outline-sharp" /></template>
<style>
.zzfe4bbaf {
  fill: currentColor;
  d: path("M8 22v-3l-3-6V7h1V2h12v5h1v6l-3 6v3zM8 7h2V5h1v2h2V5h1v2h2V4H8zm2 13h4v-1.5l3-6V9H7v3.5l3 6zm2-7.5");
}

</style>

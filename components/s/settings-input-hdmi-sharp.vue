<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mk3z1k03c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:settings-input-hdmi-sharp" /></template>
<style>
.mk3z1k03c {
  fill: currentColor;
  d: path("M8 22v-3l-3-6V7h1V2h12v5h1v6l-3 6v3zM8 7h2V5h1v2h2V5h1v2h2V4H8z");
}

</style>

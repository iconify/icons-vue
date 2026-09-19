<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pm1ckk35q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-settings-input-hdmi" /></template>
<style>
.pm1ckk35q {
  fill: currentColor;
  d: path("M18 7V2H6v5H5v6l3 6v3h8v-3l3-6V7zM8 4h8v3h-2V5h-1v2h-2V5h-1v2H8z");
}

</style>

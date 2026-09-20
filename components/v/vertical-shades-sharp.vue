<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnkr6kbks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:vertical-shades-sharp" /></template>
<style>
.bnkr6kbks {
  fill: currentColor;
  d: path("M3 20v-1h2V4h14v15h2v1zm6.75-1h4.5V5h-4.5z");
}

</style>

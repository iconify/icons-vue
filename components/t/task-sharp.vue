<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3fmbmbpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:task-sharp" /></template>
<style>
.w3fmbmbpc {
  fill: currentColor;
  d: path("m10.95 16.866l4.958-4.958l-.72-.72l-4.244 4.245l-2.138-2.139l-.714.714zM5 21V3h9.5L19 7.5V21zm9-13h4l-4-4z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zfwsombmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:real-estate-agent-sharp" /></template>
<style>
.zfwsombmp {
  fill: currentColor;
  d: path("M19 15v-2.4L9.35 9H7V6.5l7-5l7 5V15zm-4.5-7h1V7h-1zm-2 0h1V7h-1zm2 2h1V9h-1zm-2 0h1V9h-1zM1 22V11h4v11zm13 0l-7-1.975V11h1.975L17 14v2h-4l-1.75-.675l-.35.925L13 17h9v2z");
}

</style>

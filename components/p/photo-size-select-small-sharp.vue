<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzfl5bc-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:photo-size-select-small-sharp" /></template>
<style>
.pzfl5bc-k {
  fill: currentColor;
  d: path("M4 20v-9h9v9zm11 0v-1h2v1zM5 18h7l-2.254-3.077l-1.669 2.193l-1.246-1.62zm14-1v-2h1v2zm0-4v-2h1v2zM4 9V7h1v2zm15 0V7h1v2zM7 5V4h2v1zm4 0V4h2v1zm4 0V4h2v1zM4 5V4h1v1zm16 0h-1V4h1zm-1 15v-1h1v1z");
}

</style>

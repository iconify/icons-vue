<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbw9mle8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mimo-disconnect-outline-sharp" /></template>
<style>
.dbw9mle8a {
  fill: currentColor;
  d: path("M6 21v-2l1-1H2V3.175h1.175L5 5H4v11h9.2L.7 3.5l1.4-1.4l19.8 19.8l-1.4 1.4l-5.3-5.3H17l1 1v2zm14.7-3.15l-.7-.7V5H7.85l-2-2H22v14.85zM8.6 11.4");
}

</style>

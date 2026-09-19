<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twchx3b5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-brunch-dining" /></template>
<style>
.twchx3b5i {
  fill: currentColor;
  d: path("M18 8h2V4h-2zm-2 14H2v-2h14zm2-6.11l-.4-.42a5.85 5.85 0 0 1-1.6-4V2h6v9.51c0 1.46-.54 2.87-1.53 3.94l-.47.52V20h2v2h-4zM7 16v-2h4v2h5v2H2v-2z");
}

</style>

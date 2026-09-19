<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjakrkdqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-forum" /></template>
<style>
.kjakrkdqh {
  fill: currentColor;
  d: path("M22 6h-3v9H6v3h12l4 4zm-5 7V2H2v15l4-4z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dkzv0d1ay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-vibration" /></template>
<style>
.dkzv0d1ay {
  fill: currentColor;
  d: path("M0 15h2V9H0zm3 2h2V7H3zm19-8v6h2V9zm-3 8h2V7h-2zM18 3H6v18h12zm-2 16H8V5h8z");
}

</style>

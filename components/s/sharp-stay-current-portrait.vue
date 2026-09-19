<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="me47m4bso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-stay-current-portrait" /></template>
<style>
.me47m4bso {
  fill: currentColor;
  d: path("M19 1.01L5.01 1v22H19zM17 19H7V5h10z");
}

</style>

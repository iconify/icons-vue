<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2p6r_ejb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:signal-cellular-4-bar" /></template>
<style>
.b2p6r_ejb {
  fill: currentColor;
  d: path("M3 21L21 3v18z");
}

</style>

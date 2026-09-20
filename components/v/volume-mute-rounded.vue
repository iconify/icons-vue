<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="naknutbdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:volume-mute-rounded" /></template>
<style>
.naknutbdq {
  fill: currentColor;
  d: path("M11.423 14H8.808q-.343 0-.576-.232T8 13.192v-2.384q0-.343.232-.576T8.808 10h2.615l2.685-2.685q.244-.244.568-.112t.324.472v8.65q0 .34-.324.472t-.568-.112z");
}

</style>

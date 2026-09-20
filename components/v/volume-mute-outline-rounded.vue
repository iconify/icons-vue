<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3t76g-od"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:volume-mute-outline-rounded" /></template>
<style>
.g3t76g-od {
  fill: currentColor;
  d: path("M11.423 14H8.808q-.343 0-.576-.232T8 13.192v-2.384q0-.343.232-.576T8.808 10h2.615l2.685-2.685q.244-.244.568-.112t.324.472v8.65q0 .34-.324.472t-.568-.112zM9 13h2.85L14 15.15v-6.3L11.85 11H9zm2.5-1");
}

</style>

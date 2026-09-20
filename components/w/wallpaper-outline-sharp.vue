<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="su0t7cb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wallpaper-outline-sharp" /></template>
<style>
.su0t7cb8d {
  fill: currentColor;
  d: path("M4 20v-7h1v6h6v1zm9 0v-1h6v-6h1v7zm-5.5-3.5l1.962-2.577l1.75 2.116l2.615-3.308l2.827 3.769zM4 11V4h7v1H5v6zm15 0V5h-6V4h7v7zm-4.488-1.507q-.32-.315-.32-.796t.315-.8t.796-.32q.481 0 .8.315t.32.796t-.315.8t-.796.32t-.8-.315");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-dm_z_3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:weight-sharp" /></template>
<style>
.l-dm_z_3l {
  fill: currentColor;
  d: path("M12 7q.425 0 .713-.288T13 6t-.288-.712T12 5t-.712.288T11 6t.288.713T12 7M3.7 21l2-14h3.475q-.075-.25-.125-.488T9 6q0-1.25.875-2.125T12 3t2.125.875T15 6q0 .275-.05.513T14.825 7H18.3l2 14z");
}

</style>

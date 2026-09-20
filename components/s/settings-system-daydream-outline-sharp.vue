<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbavtlb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:settings-system-daydream-outline-sharp" /></template>
<style>
.dbavtlb8s {
  fill: currentColor;
  d: path("M9 16h6.5q1.05 0 1.775-.725T18 13.5t-.725-1.775T15.5 11h-.05q-.2-1.275-1.113-2.137T12.15 8q-1.05 0-1.95.525T8.85 10h-.125q-1.175 0-1.95.9T6 13q0 1.25.875 2.125T9 16m0-2q-.425 0-.712-.288T8 13t.288-.712T9 12h1.25v-.25q0-.725.513-1.237T12 10t1.238.513t.512 1.237V13h1.75q.2 0 .35.15t.15.35t-.15.35t-.35.15zm-7 6V4h20v16zm2-2h16V6H4zm0 0V6z");
}

</style>

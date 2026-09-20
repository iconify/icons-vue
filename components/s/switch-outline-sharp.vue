<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ol-woebdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:switch-outline-sharp" /></template>
<style>
.ol-woebdw {
  fill: currentColor;
  d: path("M4 22V2h16v20zm2-2h12V4H6zm2-3h8V7H8zm2-2v-4h4v4zm2-8.75q.3 0 .525-.213t.225-.537q0-.3-.225-.525T12 4.75q-.325 0-.537.225t-.213.525q0 .325.213.538T12 6.25m0 13q.3 0 .525-.213t.225-.537q0-.3-.225-.525T12 17.75q-.325 0-.537.225t-.213.525q0 .325.213.538t.537.212M12 12");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzpiifbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:screen-share-outline-sharp" /></template>
<style>
.zzpiifbzy {
  fill: currentColor;
  d: path("M1 21v-2h22v2zm1-3V3h20v15zm2-2h16V5H4zm0 0V5zm4-2h2v-2q0-.425.288-.712T11 11h2v2l3-3l-3-3v2h-2q-1.25 0-2.125.875T8 12z");
}

</style>

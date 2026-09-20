<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wl_zn_sne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:screencast" /></template>
<style>
.wl_zn_sne {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.413-.588T2 18V6q0-.825.588-1.413T4 4h16q.825 0 1.413.588T22 6v12q0 .825-.588 1.413T20 20H4Zm10-4v-2h4v2h-4Zm0-3v-2h4v2h-4ZM4 11v7h16v-8h-6V8h6V6h-8v5H4Z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hoosbfbzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:smart-display-rounded" /></template>
<style>
.hoosbfbzf {
  fill: currentColor;
  d: path("m10.275 16l5.575-3.575q.225-.15.225-.425t-.225-.425L10.275 8q-.25-.175-.513-.025t-.262.45v7.15q0 .3.263.45t.512-.025M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20z");
}

</style>

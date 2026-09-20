<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7d5z8bpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-change-next-24-regular" /></template>
<style>
.f7d5z8bpx {
  fill: currentColor;
  d: path("M2.75 5h18.5a.75.75 0 0 1 .102 1.493l-.102.007H2.75a.75.75 0 0 1-.102-1.493zm18.5 4H2.75l-.102.007A.75.75 0 0 0 2.75 10.5h18.5l.102-.007A.75.75 0 0 0 21.25 9m-18.5 5.5h8.982A6.5 6.5 0 0 1 12.81 13H2.75l-.102.007A.75.75 0 0 0 2.75 14.5m0 2.5h8.269a6.6 6.6 0 0 0 .057 1.5H2.75a.75.75 0 0 1-.102-1.493zm9.25.5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 0 0-11 0m6.35 2.854l-.07.057a.5.5 0 0 1-.637-.057l-.058-.07a.5.5 0 0 1 .058-.638L19.289 18H14.5l-.09-.008A.5.5 0 0 1 14 17.5l.008-.09A.5.5 0 0 1 14.5 17h4.789l-1.646-1.646l-.058-.07a.5.5 0 0 1 .765-.638l2.516 2.517l.05.066l.035.061l.029.08l.014.086l-.002.11l-.019.085l-.023.059l-.044.077l-.04.05z");
}

</style>

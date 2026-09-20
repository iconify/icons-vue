<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilr3avbgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-change-previous-24-regular" /></template>
<style>
.ilr3avbgp {
  fill: currentColor;
  d: path("M17.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m-.78 2.589l-.07.057l-2.516 2.517l-.04.05l-.044.077l-.023.059l-.02.085l-.002.11l.015.086l.03.08l.033.061l.051.066l2.516 2.517a.5.5 0 0 0 .765-.638l-.058-.07L15.711 18H20.5a.5.5 0 0 0 .492-.41L21 17.5a.5.5 0 0 0-.41-.492L20.5 17h-4.789l1.646-1.646a.5.5 0 0 0 .058-.638l-.058-.07a.5.5 0 0 0-.638-.057M11.018 17H2.75l-.102.007A.75.75 0 0 0 2.75 18.5h8.326a6.6 6.6 0 0 1-.057-1.5m.713-2.5H2.75a.75.75 0 0 1-.102-1.493L2.75 13h10.06a6.5 6.5 0 0 0-1.078 1.5M21.25 9H2.75l-.102.007A.75.75 0 0 0 2.75 10.5h18.5l.102-.007A.75.75 0 0 0 21.25 9m0-4H2.75l-.102.007A.75.75 0 0 0 2.75 6.5h18.5l.102-.007A.75.75 0 0 0 21.25 5");
}

</style>

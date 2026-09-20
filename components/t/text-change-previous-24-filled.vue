<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_cqbkb3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-change-previous-24-filled" /></template>
<style>
.z_cqbkb3u {
  fill: currentColor;
  d: path("M17.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m-.78 2.589l-.07.057l-2.516 2.517l-.04.05l-.044.077l-.023.059l-.02.085l-.002.11l.015.086l.03.08l.033.061l.051.066l2.516 2.517a.5.5 0 0 0 .765-.638l-.058-.07L15.711 18H20.5a.5.5 0 0 0 .492-.41L21 17.5a.5.5 0 0 0-.41-.492L20.5 17h-4.789l1.646-1.646a.5.5 0 0 0 .058-.638l-.058-.07a.5.5 0 0 0-.638-.057M11.018 17H3l-.117.007A1 1 0 0 0 3 19h8.174a6.5 6.5 0 0 1-.155-2m.48-2H3a1 1 0 0 1-.117-1.993L3 13h9.81a6.5 6.5 0 0 0-1.312 2M3 11a1 1 0 0 1-.117-1.993L3 9h18a1 1 0 0 1 .117 1.993L21 11zm18-6H3l-.117.007A1 1 0 0 0 3 7h18l.117-.007A1 1 0 0 0 21 5");
}

</style>

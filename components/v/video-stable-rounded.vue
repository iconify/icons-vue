<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2ebm_9dm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:video-stable-rounded" /></template>
<style>
.x2ebm_9dm {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20zm13.225-2.975l1.8-6.725q.125-.4-.087-.75t-.613-.475L8.05 6.275q-.4-.125-.75.088t-.475.612l-1.8 6.725q-.125.4.088.75t.612.475L16 17.725q.4.125.75-.088t.475-.612");
}

</style>

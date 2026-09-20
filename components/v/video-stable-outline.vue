<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmi5f9b7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:video-stable-outline" /></template>
<style>
.gmi5f9b7y {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20zm0-2h16V6H4zm12.975 0l2.3-8.65L7.075 6l-2.3 8.65zm-1.425-2.45l-8.325-2.3L8.5 8.45l8.325 2.3zM4 18V6z");
}

</style>

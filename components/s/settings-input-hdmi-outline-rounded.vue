<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xw7bsncyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:settings-input-hdmi-outline-rounded" /></template>
<style>
.xw7bsncyr {
  fill: currentColor;
  d: path("M10 22q-.825 0-1.412-.587T8 20v-1l-2.8-5.575q-.125-.2-.162-.437T5 12.525V9q0-.55.275-1T6 7.275V4q0-.825.588-1.412T8 2h8q.825 0 1.413.588T18 4v3.275q.45.275.725.725T19 9v3.525q0 .225-.038.463t-.162.437L16 19v1q0 .825-.587 1.413T14 22zM8 7h2V5.5q0-.2.15-.35T10.5 5t.35.15t.15.35V7h2V5.5q0-.2.15-.35T13.5 5t.35.15t.15.35V7h2V4H8zm2 13h4v-1.5l3-6V9H7v3.5l3 6zm2-7.5");
}

</style>

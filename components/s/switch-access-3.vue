<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fll146b-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:switch-access-3" /></template>
<style>
.fll146b-s {
  fill: currentColor;
  d: path("M12 22q-.825 0-1.412-.587T10 20v-1.175L16.825 12L10 5.175V4q0-.825.588-1.412T12 2h8q.825 0 1.413.588T22 4v3.125q.425.125.713.525T23 8.5v2q0 .45-.288.85t-.712.525V20q0 .825-.587 1.413T20 22zm-2-6l-1.4-1.4l1.575-1.6H2v-2h8.175L8.6 9.4L10 8l4 4zM2 9V5h4v4zm0 10v-4h4v4z");
}

</style>

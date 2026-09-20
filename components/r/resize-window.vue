<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rf_dn-bbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:resize-window" /></template>
<style>
.rf_dn-bbw {
  fill: currentColor;
  d: path("M19.292 20L4 4.714L4.713 4L20 19.287zm-9.62 0L4 14.329l.714-.714l5.67 5.671z");
}

</style>

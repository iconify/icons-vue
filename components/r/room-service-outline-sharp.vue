<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9_n6tbwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:room-service-outline-sharp" /></template>
<style>
.s9_n6tbwb {
  fill: currentColor;
  d: path("M3.23 17.385v-1h17.54v1zM4 15v-.23q0-2.95 2.01-5.103Q8.022 7.516 11 7.097V5.653h2v1.442q2.985.42 4.992 2.571T20 14.77V15zm1.07-1h13.86q-.234-2.446-2.247-4.204T12 8.04T7.32 9.796T5.07 14M12 14");
}

</style>

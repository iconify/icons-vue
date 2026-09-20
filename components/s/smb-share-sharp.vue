<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q87vi-bqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:smb-share-sharp" /></template>
<style>
.q87vi-bqx {
  fill: currentColor;
  d: path("M11.433 12.692h4.498q.48 0 .813-.332t.333-.811t-.333-.827t-.813-.347h-.55l-.077-.48q-.087-.666-.596-1.127q-.51-.46-1.21-.46q-.552 0-.98.289q-.43.29-.666.769l-.154.307l-.365.02q-.596.05-1.003.462t-.407 1.028t.442 1.062q.44.447 1.068.447M2 19.77V8.077h1v10.692h16.039v1zm3-3V3h7l1.23 1.23H22v12.54z");
}

</style>

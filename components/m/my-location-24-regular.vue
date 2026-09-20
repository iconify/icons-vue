<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekkuc_baq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:my-location-24-regular" /></template>
<style>
.ekkuc_baq {
  fill: currentColor;
  d: path("M12 2a.75.75 0 0 1 .743.648l.007.102v1.788a7.5 7.5 0 0 1 6.713 6.714l.037-.002h1.75a.75.75 0 0 1 .102 1.493l-.102.007l-1.788-.001a7.5 7.5 0 0 1-6.714 6.714l.002.037v1.75a.75.75 0 0 1-1.493.102l-.007-.102l.001-1.788a7.5 7.5 0 0 1-6.714-6.714l-.037.002H2.75a.75.75 0 0 1-.102-1.493l.102-.007h1.788a7.5 7.5 0 0 1 6.714-6.713L11.25 4.5V2.75A.75.75 0 0 1 12 2m0 4a6 6 0 1 0 0 12a6 6 0 0 0 0-12m0 2a4 4 0 1 1 0 8a4 4 0 0 1 0-8");
}

</style>

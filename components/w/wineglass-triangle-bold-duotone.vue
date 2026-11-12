<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k2p8dyb2p"/><path class="wn54x-yav"/><path class="kw88p8b_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wineglass-triangle-bold-duotone" /></template>
<style>
.k2p8dyb2p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.2498 13.8047L3.48317 5.86426C2.43695 4.79452 3.20008 3 4.70094 3H19.2986C20.7995 3 21.5626 4.79452 20.5164 5.86426L12.7498 13.8047V20.25H11.2498V13.8047Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.kw88p8b_o {
  fill: currentColor;
  d: path("M16.4707 10L12.7148 13.8408C12.3226 14.2415 11.6773 14.2416 11.2852 13.8408L7.5293 10H16.4707Z");
}

.wn54x-yav {
  fill: currentColor;
  d: path("M16.2441 20.25C16.6581 20.2503 16.9941 20.5859 16.9941 21C16.9941 21.4141 16.6581 21.7497 16.2441 21.75H7.75586C7.34165 21.75 7.00586 21.4142 7.00586 21C7.00586 20.5858 7.34165 20.25 7.75586 20.25H16.2441Z");
}

</style>

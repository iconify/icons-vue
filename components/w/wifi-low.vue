<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-v-zzbhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:wifi-low" /></template>
<style>
.g-v-zzbhd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 8.251q-3.831 0-6.54 2.709q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.105.106.243.163t.287.057t.287-.057t.243-.163Q8.79 9.751 12 9.751t5.48 2.269q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243Q15.831 8.251 12 8.251M9.75 17.5q0-2.25 2.25-2.25t2.25 2.25T12 19.75T9.75 17.5");
}

</style>

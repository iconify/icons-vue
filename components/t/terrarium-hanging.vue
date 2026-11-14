<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxtm5vbkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:terrarium-hanging" /></template>
<style>
.zxtm5vbkn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.25q-2.25 0-2.25 2.25q0 1.837 1.5 2.174v.952q-.212.083-.423.212l-7.2 4.4q-1.527.933-.962 2.631l2.281 6.842q.513 1.539 2.135 1.539h9.838q1.622 0 2.135-1.539l2.281-6.842q.565-1.698-.962-2.631l-7.2-4.4q-.211-.129-.423-.212v-.952q1.5-.337 1.5-2.174q0-2.25-2.25-2.25m-.75 15.461q-3-.331-3-3.461q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T9 12.5q1.632 0 2.554.663Q12.318 11.5 15 11.5q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 2.907-3 3.214v3.286q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T12 19.5t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146z");
}

</style>

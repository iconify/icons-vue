<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-8o6clwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:wrench" /></template>
<style>
.w-8o6clwp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21 8.5q0 2.278-1.611 3.889T15.5 14q-1.894 0-3.326-1.113L5.03 20.03q-.105.106-.243.163t-.287.057t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113l7.143-7.144Q10 10.394 10 8.5q0-2.278 1.611-3.889T15.5 3q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146V7q0 .75.75.75h3.25q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141T21 8.5m-5.5 4q-1.842 0-2.836-.848q-.053-.101-.134-.182t-.182-.134Q11.5 10.342 11.5 8.5q0-3.606 3.25-3.961V7q0 2.25 2.25 2.25h2.461q-.355 3.25-3.961 3.25");
}

</style>

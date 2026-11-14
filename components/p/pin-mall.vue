<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uauqm5b4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-mall" /></template>
<style>
.uauqm5b4p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.75 6.75h4.5V6q0-2.25-2.25-2.25T9.75 6zm6 0h3.75q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v12q0 2.75-2.75 2.75h-11q-2.75 0-2.75-2.75v-12q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h3.75V6q0-3.75 3.75-3.75T15.75 6z");
}

</style>

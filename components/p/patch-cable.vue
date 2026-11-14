<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owxu0zbea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:patch-cable" /></template>
<style>
.owxu0zbea {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.75 2.5v2.326q1.5.337 1.5 2.174v1q0 1.837-1.5 2.174V14q0 2.175 1.538 3.712Q9.825 19.25 12 19.25t3.712-1.538Q17.25 16.175 17.25 14v-3.826q-1.5-.337-1.5-2.174V7q0-1.837 1.5-2.174V2.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T18 1.75t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v2.326q1.5.337 1.5 2.174v1q0 1.837-1.5 2.174V14q0 2.796-1.977 4.773T12 20.75t-4.773-1.977T5.25 14v-3.826Q3.75 9.837 3.75 8V7q0-1.837 1.5-2.174V2.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q5.926 1.75 6 1.75t.146.014t.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146");
}

</style>

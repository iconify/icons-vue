<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcz5bebsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ski-tip" /></template>
<style>
.hcz5bebsp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.5 12.25H12q3.863 0 5.279-4.956q.02-.071.054-.137q.034-.065.08-.123t.102-.106t.121-.084t.135-.058t.143-.031q.074-.009.147-.002q.074.006.145.026l3.5 1q.069.019.132.052q.064.032.12.075q.057.044.104.097t.083.115q.037.061.061.128t.035.138t.009.141q-.003.072-.019.141Q20.167 17.75 12 17.75H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T1.75 17v-4q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfz1yg28f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pollen-grains" /></template>
<style>
.rfz1yg28f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.5 2.25q-3.25 0-3.25 3.25T7.5 8.75t3.25-3.25T7.5 2.25m5.75 3.25q0-3.25 3.25-3.25t3.25 3.25t-3.25 3.25t-3.25-3.25m-.901 5.836q-5.099-2.684-10.198 0q-.066.035-.123.081q-.057.047-.105.104t-.082.121t-.057.136q-.022.07-.03.144t-.001.147t.028.144t.055.136t.081.123t.104.105t.121.082t.136.057q.07.022.144.03t.147.001t.144-.028t.136-.055q4.401-2.316 8.802 0q5.099 2.684 10.198 0q.066-.035.123-.081q.057-.047.105-.104t.082-.121q.035-.065.057-.136q.022-.07.03-.144t.001-.147t-.028-.144t-.055-.136q-.035-.066-.081-.123q-.047-.057-.104-.105t-.121-.082q-.065-.035-.136-.057q-.07-.022-.144-.03t-.147-.001t-.144.028t-.136.055q-4.401 2.316-8.802 0M12 15.25q-3.25 0-3.25 3.25T12 21.75t3.25-3.25T12 15.25");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4mzcyvne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:operating-theatre" /></template>
<style>
.n4mzcyvne {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.25 1.75h-6.5q-2.5 0-2.5 2.5q0 1.036.732 1.768t1.768.732h6.5q1.036 0 1.768-.732t.732-1.768q0-2.5-2.5-2.5m4 20.5H12q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V8q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T12 7.25h7.25q1.036 0 1.768.732t.732 1.768v10q0 1.036-.732 1.768t-1.768.732M12 7.25q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T11.25 8v13.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014H4.75q-1.036 0-1.768-.732T2.25 19.75v-10q0-2.5 2.5-2.5zm-4.5 3q-2.75 0-2.75 2.75t2.75 2.75T10.25 13T7.5 10.25M13.75 13q0 2.75 2.75 2.75T19.25 13t-2.75-2.75T13.75 13");
}

</style>

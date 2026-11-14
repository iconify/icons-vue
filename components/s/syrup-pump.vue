<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6dvxhinf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:syrup-pump" /></template>
<style>
.f6dvxhinf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.25 6.25h-.5v-2h5.5V5.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-2q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T19 2.75H9q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043T9 4.25h2.25v2h-.5q-2 0-2 2q0 .329.054.603q-1.446.291-2.553 1.398q-1.501 1.501-1.501 3.624v2.75q0 2.123 1.501 3.624t3.624 1.501h4.25q2.123 0 3.624-1.501t1.501-3.624v-2.75q0-2.123-1.501-3.624q-1.107-1.107-2.553-1.398q.054-.274.054-.603q0-2-2-2");
}

</style>

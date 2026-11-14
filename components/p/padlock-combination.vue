<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wifs1wb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:padlock-combination" /></template>
<style>
.wifs1wb6i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.749 10.751q-.89-.89-1.999-1.252V7q0-1.968-1.391-3.359T12 2.25T8.641 3.641T7.25 7v2.499q-1.109.362-1.999 1.252q-1.501 1.501-1.501 3.624v2.25q0 2.123 1.501 3.624t3.624 1.501h6.25q2.123 0 3.624-1.501t1.501-3.624v-2.25q0-2.123-1.501-3.624M8.875 9.25l-.125.001V7q0-3.25 3.25-3.25T15.25 7v2.251l-.125-.001zM8.5 15.5Q8.5 12 12 12t3.5 3.5T12 19t-3.5-3.5m1.5 0q0-2 2-2t2 2t-2 2t-2-2m2.01-.75H12q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h.01q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014");
}

</style>

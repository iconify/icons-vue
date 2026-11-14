<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1l9wkbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:symmetry-guide" /></template>
<style>
.u1l9wkbdd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 21.5v-19q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q12.074 1.75 12 1.75t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v19q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146m3.051-11.741Q14.001 10.156 14 12v5.25q0 2.5 2.5 2.5h2.008q1.37 0 2.107-1.155t.16-2.398l-2.397-5.164q-.777-1.672-2.577-1.274M10 12v5.25q0 1.036-.732 1.768T7.5 19.75H5.492q-1.37 0-2.107-1.155t-.16-2.398l2.397-5.164q.777-1.672 2.577-1.274T10 12");
}

</style>

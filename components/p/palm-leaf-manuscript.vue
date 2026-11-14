<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rn81u_iiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:palm-leaf-manuscript" /></template>
<style>
.rn81u_iiu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 3.75V2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q12.074 1.75 12 1.75t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v1.25H5Q2.75 3.75 2.75 6T5 8.25h6.25v1.5H5q-2.25 0-2.25 2.25T5 14.25h6.25v1.5H5q-2.25 0-2.25 2.25T5 20.25h6.25v1.25q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-1.25H19q2.25 0 2.25-2.25T19 15.75h-6.25v-1.5H19q2.25 0 2.25-2.25T19 9.75h-6.25v-1.5H19q2.25 0 2.25-2.25T19 3.75z");
}

</style>

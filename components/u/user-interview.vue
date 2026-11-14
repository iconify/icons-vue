<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jqybi2b9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:user-interview" /></template>
<style>
.jqybi2b9n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.25 2.25h4.25q2.75 0 2.75 2.75v5q0 2.75-2.75 2.75h-1.189l-2.031 2.03q-.105.106-.243.163T15.75 15t-.287-.057t-.243-.163t-.163-.243T15 14.25v-1.506q-2.5-.122-2.5-2.744V5q0-2.75 2.75-2.75M4.848 6.848Q3.75 7.947 3.75 9.5q0 3.75 3.75 3.75t3.75-3.75T7.5 5.75q-1.553 0-2.652 1.098M7.5 14.75q-5.75 0-5.75 5.75q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-4.25 4.25-4.25t4.25 4.25q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-5.75-5.75-5.75");
}

</style>

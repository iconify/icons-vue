<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_0e0lbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:thermometer-digital" /></template>
<style>
.g_0e0lbgi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.75 5.5q0-3.75-3.75-3.75T8.25 5.5v8q0 2.593 1.793 3.393l.463 3.7l.002.018Q10.717 22 12 22t1.492-1.389l.002-.018l.463-3.7q1.793-.8 1.793-3.393zm-1.5 1.25v2Q14.25 11 12 11T9.75 8.75v-2Q9.75 4.5 12 4.5t2.25 2.25m-2.24 6q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H12q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014zm-.016 7.657l-.396-3.168q.195.011.402.011t.402-.011l-.396 3.168h.001L12 20.5z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzvvm9b4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tatami" /></template>
<style>
.jzvvm9b4t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.5 5.75H7q-.1 0-.196.026t-.183.077q-.086.05-.156.121t-.119.158l-4.5 8q-.096.172-.096.368V18q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014H17q.1 0 .196-.026t.183-.077q.086-.05.156-.121t.119-.158l4.5-8q.096-.172.096-.368V6.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014m-16.311 5.5h12.779l-1.407 2.5H3.782zm13.622-1.5H6.032l1.407-2.5h12.779zm1.093 1.117l.846-1.504v.441l-4.189 7.446H3.25v-2H17q.1 0 .196-.026t.183-.077q.086-.05.156-.121t.119-.158l2.249-3.999z");
}

</style>

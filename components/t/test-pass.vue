<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqtcdnmmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:test-pass" /></template>
<style>
.mqtcdnmmo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752m5.975 9.665l5.221-5.675q.101-.11.236-.172q.136-.063.285-.069t.289.045t.25.152q.054.05.098.11q.043.059.074.126t.049.139t.02.146t-.008.147t-.037.142q-.025.069-.064.132q-.038.063-.088.118l-5.75 6.25l-.022.022q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094l-3.25-3.25q-.106-.105-.163-.243t-.057-.287t.057-.287t.163-.243q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069q.061.041.113.094z");
}

</style>

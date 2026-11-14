<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="of1d9zucb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:reward-streak" /></template>
<style>
.of1d9zucb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.481 2.209q.134-.129.313-.18q.143-.041.292-.024q.148.017.278.089q.131.073.223.19q.093.117.134.26q1.304 4.565 1.496 7.495q.533-.396.533-1.539q0-.149.057-.287t.163-.243q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q2.72 2.719 2.72 6.03q0 2.796-1.977 4.773T12 20.75t-4.773-1.977T5.25 14q0-5.82 6.231-11.791");
}

</style>

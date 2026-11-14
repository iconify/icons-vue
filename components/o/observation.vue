<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekuyjac3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:observation" /></template>
<style>
.ekuyjac3z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.815 11.695Q4.901 4.75 12 4.75t10.185 6.945q.065.146.065.305t-.065.305Q19.099 19.25 12 19.25T1.815 12.305Q1.75 12.159 1.75 12t.065-.305m7.18-2.7Q7.75 10.24 7.75 12t1.245 3.005T12 16.25t3.005-1.245T16.25 12t-1.245-3.005T12 7.75T8.995 8.995");
}

</style>

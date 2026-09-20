<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/i99jpsfam.css';
import '../../css/k/k_vfb7aeb.css';
import '../../css/h/hi5e58bpt.css';
import '../../css/u/u65-1ubal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="i99jpsfam"/><path class="k_vfb7aeb"/><path class="hi5e58bpt"/><path class="u65-1ubal"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sort-alphabetically-broken" /></template>

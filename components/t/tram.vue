<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/pcg8mdk_e.css';
import '../../css/n/ngtd4hbhd.css';
import '../../css/o/o5czz65za.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pcg8mdk_e"/><path class="ngtd4hbhd"/><path class="o5czz65za"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:tram" /></template>

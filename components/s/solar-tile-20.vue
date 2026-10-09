<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtc4_gbjh.css';
import '../../css/y/y4wwydbht.css';
import '../../css/y/yctemwfli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xtc4_gbjh"/><path class="y4wwydbht"/><path class="yctemwfli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-tile-20" /></template>

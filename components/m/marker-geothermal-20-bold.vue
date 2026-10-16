<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hei8_htdz.css';
import '../../css/f/fsd_gybim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hei8_htdz"/><path class="fsd_gybim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:marker-geothermal-20-bold" /></template>

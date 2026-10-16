<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hei8_htdz.css';
import '../../css/p/p3rpssb_c.css';
import '../../css/s/syuk1s6xu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hei8_htdz"/><path class="p3rpssb_c"/><path class="syuk1s6xu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:marker-biomass-20-bold" /></template>

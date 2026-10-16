<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgjp5_b_u.css';
import '../../css/h/h7qs6-b0q.css';
import '../../css/n/nwor9yc1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wgjp5_b_u"/><path class="h7qs6-b0q"/><path class="nwor9yc1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:marker-biomass-20" /></template>
